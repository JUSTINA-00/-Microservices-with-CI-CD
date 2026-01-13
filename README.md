# -Microservices-with-CI-CD
This workspace contains three independent services: User, Product, and Order.

Build images:

docker build -t user-service ./microservices/user-service
docker build -t product-service ./microservices/product-service
docker build -t order-service ./microservices/order-service
Run services locally:

docker run -p 5001:5001 user-service
docker run -p 5002:5002 product-service
docker run -p 5003:5003 order-service
