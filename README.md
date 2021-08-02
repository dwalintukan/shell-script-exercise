# Shell Script Exercise

Create a shell script to do the following:

1. Modify the NextJS application slightly, e.g. add some line of text.
2. Build the NextJS application:

    ```bash
    cd /sample-app
    yarn build
    ```

3. Copy the NextJS files in `/sample-app` to `/var/www/app/html` on a running EC2 instance.
4. Create a process that will run the command `yarn start` in `/var/www/app/html` as a background job on every restart of the EC2 instance.
