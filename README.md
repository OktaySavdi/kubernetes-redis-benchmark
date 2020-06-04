# Kubernetes Redis Benchmark Example

![image](https://user-images.githubusercontent.com/3519706/83653112-0e481700-a5c4-11ea-9c68-c0bb1e1be2f8.png)

We will do a load test on redis with redis-benchmark. You can do your redis sentinel or redis cluster performance tests

You can access the redis benchmark code prepared with dotnet core. Code repo for image [github\RedisBenchmarkUI](https://github.com/OktaySavdi/RedisBenchmarkUI)

## Start the helloworld service

you need to run the command below to install
```ruby
kubectl create -f kubernetes-redis-benchmark/Application.yml
```
**Optionally**

If there is no redis in your environment, you can install and test a new one with the command below.

```ruby
kubectl create -f kubernetes-redis-benchmark/Redis.yml
```

## Monitoring and Control

![image](https://user-images.githubusercontent.com/3519706/83651722-78f85300-a5c2-11ea-931f-edb3b5e71a54.png)

![image](https://user-images.githubusercontent.com/3519706/83651814-92999a80-a5c2-11ea-81f9-cce986524239.png)

![image](https://user-images.githubusercontent.com/3519706/83651583-52d2b300-a5c2-11ea-9e80-c069ec357687.png)

![image](https://user-images.githubusercontent.com/3519706/83651632-5fefa200-a5c2-11ea-936b-19bd2059048f.png)
