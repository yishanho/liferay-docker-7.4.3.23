# liferay-docker-7.4.3.23

* 建置

  ```bash
  docker build -t yishanho/liferay-portal:7.4.3.23-ga23 . --no-cache
  ```

* 測試

  ```bash
  docker run -p 8080:8080 -d yishanho/liferay-portal:7.4.3.23-ga23
  ```

* push 至 Docker Hub

  ```bash
  docker push yishanho/liferay-portal:7.4.3.23-ga23
  ```
