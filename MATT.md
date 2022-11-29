# docker build -f Dockerfile.dev .
# docker run -p 3000:3000 ###

# docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app ###

# docker build -t trollwind/frontend:latest -f Dockerfile.dev .
# docker run -it trollwind/frontend npm run test
# docker run trollwind/frontend npm run test -- --coverage

# for prod build:
# docker build .
# docker run -p 8080:80 ###

run dev
run test
run build

## GIT Setup
https://github.com/trollwind/docker-training.git
git init
git add .
git commit -m "initial commit"

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

## docker compose
docker-compose -f docker-compose-dev.yml up
docker-compose -f docker-compose-dev.yml up --build
docker-compose -f docker-compose-dev.yml down

## AWS
secret access: v37jRUERPD+WD6f33L5zWs7qzidUaoWEqQhKzOh/