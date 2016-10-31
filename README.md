### Starter Express app with Express, TypeScript and piping already included

```sh
yarn install
yarn run start
yarn run dev
```
### Docker

```sh
docker build -t express-typescript .

docker run -d -p 3000:3000 --name express-typescript \
  -e PORT=3000 \
  -e ENV_TEST="test env" \
  -e ENV2_TEST="test env 2" \
  express-typescript
```
