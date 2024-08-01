<!-- DISCLAIMER -->
<!-- This README uses the template provided by 
*** [othneildrev](https://github.com/othneildrew/Best-README-Template/blob/master/README.md)
*** and is licensed under the MIT creative commons license. (2022-09-30)
*** Please support the channel.
-->

# Azure Study Cram
<!-- <a name="readme-top"></a> -->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/weinmann-phil/azure-study-cram">
    <img src="img/Microsoft_Azure.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Azure Study Cram</h3>

  <p align="center">
    Azure Study Cram 
    <br />
    <a href="https://github.com/weinmann-phil/azure-study-cram"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/weinmann-phil/azure-study-cram">View Demo</a>
    ·
    <a href="https://github.com/weinmann-phil/azure-study-cram/issues">Report Bug</a>
    ·
    <a href="https://github.com/weinmann-phil/azure-study-cram/issues">Request Feature</a>
  </p>
</div>

<!-- OVERVIEW -->
## 0. Overview

> 😾 **Disclaimer:** 😾
>
> This project falls under the category of `learning` and is for private purposes only.
> I do not represent Microsoft or any institution entitled to offer courses or course material
> for professional assistance.
> 
> I am just your regular, friendly neighbourhood DevCatOps... 😺

The focus of this project is to prepare for Azure certifications that might be of interest,
document these, add scripts and resources that might be helpful either to prepare for the
certification exam or even in day-to-day practice (hopefully).

Here's why:

* Certifications can be important for career 😻
* A project helps to organize thought and structure that which was learned (to some degree) 🍸

Why I am not using ChatGPT for this:

* ChatGPT may be an excellent tool to prepare an outline for what to study and providing 
  a proper study guide, but I am looking for structuring the information on my own

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol start="0">
    <li>
      <a href="#0.-overview">Overview</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<p align="right">(<a href="#go-api">back to top</a>)</p>

<!-- Dependencies/technologies -->
### Built With

This is basically study material.
So there will be much reading material involved.
Since I like to be a hands on kind of DevCatOps (😼), I do provide some 
additional resources within the `[certificationId]/scripts` folder.

Since we are talking about Azure and Microsoft, the following resources might
come in handy and if you are willing to accompany me on this journey, it may
well be interesting to have these tools installed:

* Azure CLI
* PowerShell (preference on being v7 or above (since I am not a Windows user 😽))
<!-- * Python (?) -->

<!-- Please check out their respective documentation: -->

<!-- [![Terraform][Terraform]][Terraform-url] -->

<!-- [![GitLab][GitLab]][GitLab-url] -->

<p align="right">(<a href="#go-api">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started


### Prerequisites

* Install Azure CLI

  ```sh
  curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash
  ```

* Run an instance of PostgreSQL

  ```sh
  docker run --name postgres \
    -e POSTGRES_PASSWORD=$PASSWORD \
    -e POSTGRES_USER=$USER \ 
    -e POSTGRES_DB=$DATABASE_NAME \ 
    -p 5432:5432 \ 
    -d postgres
  ```

### Installation

<!-- > __NOTE__:
>
> This is a sample usage of this project.
> If you are applying this within any environments other than a local test environment,
> please mind to change the settings for the provider configuration and the backend
> configurations.
>
> Otherwise, this will not work.

1. Set up your self-hosted GitLab system

   ```sh
   sudo docker run -d \
   -p 443:443 -p 80:80 -p 22:22 \
   --hostname localhost \
   --name gitlab-ce \
   --restart always \
   -v $GITLAB_HOME/config:/etc/gitlab \
   -v $GITLAB_HOME/logs:/var/log/gitlab \
   -v $GITLAB_HOME/data:/var/opt/gitlab \
   --shm-size 256m \
   gitlab/gitlab-ce:latest
   ```

1. Create an access token with administrative privileges
   
   <details>
     <summary>Create access token</summary>

     ![create-access-token](./img/gitlab_access-token.png)

   </details>

1. Enter token and a list of users into terraform.tfvars

1. Switch directory to the workspace

   ```sh
   cd environments/gitlab/
   ```

1. Initialize project

   ```sh
   terraform init
   ```

1. Apply changes to your GitLab

   ```sh
   terraform apply
   ```

<p align="right">(<a href="#go-api">back to top</a>)</p> -->


<!-- USAGE EXAMPLES -->
## Usage

There is no particular usage yet.

<p align="right">(<a href="#go-api">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [x] Add License
- [x] Add Readme
- [ ] Add materials to `AZ-104`
  - [ ] Add study documentation and analyses
  - [ ] Add scripts and resources
- [ ] Add materials to `AZ-204`
  - [ ] Add study documentation and analyses
  - [ ] Add scripts and resources
   
See the [open issues](https://github.com/weinmann-phil/azure-study-cram/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#go-api">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

This is my first project in an attempt in giving back to the community.
Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. 
You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
1. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
1. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
1. Push to the Branch (`git push origin feature/AmazingFeature`)
1. Open a Pull Request

<p align="right">(<a href="#go-api">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#go-api">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Philip Weinmann - Philip.Weinmann@protonmail.com

Project Link: [https://github.com/weinmann-phil/azure-study-cram](https://github.com/weinmann-phil/azure-study-cram)

<p align="right">(<a href="#go-api">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

I am grateful to the people that provided the following resources, which I have 
used to create this project.

* [README template](https://github.com/othneildrew/Best-README-Template)
* [John Savill's Technical Training](https://www.youtube.com/@NTFAQGuy)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/weinmann-phil/azure-study-cram.svg?style=for-the-badge
[contributors-url]: https://github.com/weinmann-phil/azure-study-cram/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/weinmann-phil/azure-study-cram.svg?style=for-the-badge
[forks-url]: https://github.com/weinmann-phil/azure-study-cram/network/members
[stars-shield]: https://img.shields.io/github/stars/weinmann-phil/azure-study-cram.svg?style=for-the-badge
[stars-url]: https://github.com/weinmann-phil/azure-study-cram/stargazers
[issues-shield]: https://img.shields.io/github/issues/weinmann-phil/azure-study-cram.svg?style=for-the-badge
[issues-url]: https://github.com/weinmann-phil/azure-study-cram/issues
[license-shield]: https://img.shields.io/github/license/weinmann-phil/azure-study-cram.svg?style=for-the-badge
[license-url]: https://github.com/weinmann-phil/azure-study-cram/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/philipweinmann
[product-screenshot]: /img/Microsoft_Azure.png <!-- ./img/Microsoft_Azure.png -->
<!-- [Terraform]: https://img.shields.io/badge/terraform-4A235A?style=for-the-badge&logo=terraform -->


## Referecenes

* [Learn Microsoft - Install Azure CLI Linux](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-linux?pivots=apt)
* [Github - Azure](https://github.com/Azure)