# type-graphql-federation
The playground for type-graphql federation

## Architecture

<p align="center"><img style="display: block; width: 600px; margin: 0 auto;" src=img/2022-08-27-21-42-06.png alt="no image found"></p>

## Gateway
```sh
git clone git@github.com:GeekEast/type-graphql-federation-gateway.git
cd type-graphql-federation-gateway
yarn && yarn dev
```

## Product Endpoint
```sh
git clone git@github.com:GeekEast/type-graphql-federation-product.git
cd type-graphql-federation-product
yarn && yarn dev
```

## User Endpoint
```sh
git clone git@github.com:GeekEast/type-graphql-federation-user.git
cd type-graphql-federation-user
yarn && yarn dev
```