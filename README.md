# Welcome to Loco :train:

## Start development

1. Bring up support services

```
cd .devcontainer
docker compose build
docker compose up
```

2. Bring up app

```
cargo loco start
```

3. Bring up frontend

```
cd frontend
pnpm install
pnpm dev
```

## Resources

1. Main Loco [guides](https://loco.rs/docs/getting-started/tour/)
2. Loco example app integrating Stripe and showcase common app stuff
   a. [Tutorial](https://dev.to/shuttle_dev/a-full-stack-saas-template-with-loco-43ak)
   b. [Github](https://github.com/joshua-mo-143/shuttle-stripe-ex/tree/main)
