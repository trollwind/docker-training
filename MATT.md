# docker build -f Dockerfile.dev .
# docker run -p 3000:3000 ###

# docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app ###

# docker build -t trollwind/frontend:latest -f Dockerfile.dev .
# docker run -it trollwind/frontend npm run test

# for prod build:
# docker build .
# docker run -p 8080:80 ###

run dev
run test
run build