# My Docker in Docker example

- See [jpetazzo's post](https://jpetazzo.github.io/2015/09/03/do-not-use-docker-in-docker-for-ci/)
- and https://github.com/jpetazzo/dind

# Test

```
% docker run -d --privileged --name Tom otiai10/dind
% docker exec -it Tom docker run --name Jerry alpine
```

![](https://user-images.githubusercontent.com/931554/42129362-b170b82e-7c77-11e8-8703-d350cdd8a92c.png)