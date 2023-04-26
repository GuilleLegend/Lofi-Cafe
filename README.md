<div id="top"></div>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/GuilleLegend">
    <img src="https://github.com/GuilleLegend/Lofi-Cafe/blob/70db2df41b06c9ba79946bce366d2d3fce3ae096/client/assets/cover.jpg" alt="Logo" width="200" height="150">
  </a>

  <h1 align="center">Lofi Caffe</h1>

  <p align="center">
    Machine Learning supported Lo-Fi Music Generator
    <br />
    <a href="https://lofi-cafe-bco8.vercel.app/"><strong>Hear the results »</strong></a>
    <br />
    <br />
    <p align="center">Fork of <a href="https://github.com/jacbz/Lofi"><strong>jacbz/Lofi</strong></a></p>
  </p>
</div>

## Setup
If you only want to tinker around with the client, you will only need the `client` folder. This will use the project's server as the backend.

If you want to deploy your own model, you can either train your own model (see the instructions in the `model`) or download the pre-trained checkpoint from [here](https://github.com/jacbz/Lofi/files/7519187/checkpoints.zip). Once you have deployed the server, change the server address inside `client\src\api.ts`.

### Set up the client
1. Install [node.js](https://nodejs.org/en/) LTS.
1. Navigate to the client folder and run `npm install` to install the dependencies.
2. Run `npm run serve` to develop or `npm run build` to build a distributable.

By default, this uses the project's server as the backend. You can also train your own model and deploy your own server.

### Train your own model
See the [model](model) folder for details. Once you have trained your model, put the checkpoint in the `checkpoints` folder.

### Deploy your own server
See the [server](server) folder for details. You can use the provided Dockerfile. Don't forget to change the API url in the client.

## Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgments

Big thanks to [ZOOPRA UG](https://www.zoopra.de/) for hosting the server!

<a href="https://www.zoopra.de/">
  <img src="https://www.zoopra.de/wp-content/uploads/2020/11/logo_breit_800x200_black.png" href="https://www.zoopra.de" width="200px"/>
</a>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[build-shield]: https://img.shields.io/github/actions/workflow/status/jacbz/Lofi/client.yml?style=for-the-badge
[build-url]: https://github.com/jacbz/Lofi/actions
[contributors-shield]: https://img.shields.io/github/contributors/jacbz/Lofi?style=for-the-badge
[contributors-url]: https://github.com/jacbz/Lofi/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/jacbz/Lofi?style=for-the-badge
[forks-url]: https://github.com/jacbz/Lofi/network/members
[stars-shield]: https://img.shields.io/github/stars/jacbz/Lofi?style=for-the-badge
[stars-url]: https://github.com/jacbz/Lofi/stargazers
[issues-shield]: https://img.shields.io/github/issues/jacbz/Lofi?style=for-the-badge
[issues-url]: https://github.com/jacbz/Lofi/issues
[license-shield]: https://img.shields.io/github/license/jacbz/Lofi?style=for-the-badge
[license-url]: https://github.com/jacbz/Lofi/blob/master/LICENSE.txt
