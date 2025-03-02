# Arr Stack Service

This compose file has the following *arr services:

- Prowlarr: To know more, click [here][Prowlarr Site]
- Lidarr: To know more, click [here][Lidarr Site]
- Sonarr: To know more, click [here][Sonarr Site]
- Bazarr: To know more, click [here][Bazarr Site]
- Readarr: To know more, click [here][Readarr Site]

## How to install and run

- First make a copy of the ".env.example" file and rename it to ".env";
- Fill the required variables in the .env file and make sure the ports number you're using is not being used on another services;

After that you can run the command:

`docker-compose up -d`

If everything runs fine you can access the webui with machine ip and the port you chosen. This examples is from default port of every service:

- Prowlarr -> 127.0.0.1:9696 / localhost:9696 / YOUR_COMPUTER_IP:9696;
- Lidarr -> 127.0.0.1:8686 / localhost:8686 / YOUR_COMPUTER_IP:8686;
- Sonarr -> 127.0.0.1:8989 / localhost:8989 / YOUR_COMPUTER_IP:8989;
- Bazarr -> 127.0.0.1:6767 / localhost:6767 / YOUR_COMPUTER_IP:6767;
- Readarr -> 127.0.0.1:8787 / localhost:8787 / YOUR_COMPUTER_IP:8787;

[Prowlarr Site]: https://prowlarr.com
[Lidarr Site]: https://lidarr.audio
[Sonarr Site]: https://sonarr.tv
[Bazarr Site]: https://www.bazarr.media
[Readarr Site]: https://readarr.com
