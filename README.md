## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

### Building the Docker Image
To build the Docker image, open a terminal in the root of your project and run:
```sh
docker build -t nextjs-dashboard .
```

### Running Docker Container and Exposing Ports

To run a Docker container and expose ports, use the following command:

```sh
docker run -p 3000:3000 nextjs-dashboard
```
