<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<div align="center">
<h3 align="center">AIModels by VisionInit</h3> (work in progress)
  <p align="center">
  We are developing a secure and easy to use suite of software for AI Model discovery and use!<br>Download and install model once, and use anywhere!<br>Developers, this means not having to manage extra code and juggling model files.
    <br />
    <a href="https://github.com/visioninit/aimm"><strong>AI Models CLI</strong></a> - 
    <a href="https://github.com/visioninit/aimm-gui"><strong>AI Models GUI</strong></a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
  <summary>Projects in Development</summary>
  <ol>
    <li>
        Desktop and CLI applications
      <ul>
        <li><a href="#aimm-aimodels-cli">AIMM - AI Model Manager CLI (alpha)</a> [<a href="https://github.com/visioninit/aimm">Repository</a>]</li>
        <li><a href="#aimm-gui">AIMM - AI Model Manager Desktop (wip)</a></li>
      </ul>
    </li>
    <li>
      AI Model Registry
      <ul>
        <li><a href="https://aimodels.org">https://aimodels.org</a></li>
      </ul>
    </li>
    <li>
      <a href="#mission-and-goals">Mission & Goals</a>
    </li> 
    <li>
      <a href="#development-roadmap">Development Roadmap</a>
    </li>  
    <li>
      <a href="#contact">Contact Information</a>
    </li> 
  </ol>

<!-- CLI -->
### AIMM AIModels CLI

```
Usage: aimm [command] [options]

Current Dir:
  init                                        Initialize aimodels.json.
  add <model_name>:[version]                  Add a model to aimodels.json.
  remove <model_name>:[version]               Remove a model from aimodels.json.

System Wide:
  list                                        List all models.
  info <model_name>:[version]                 Get info about a model.
  install <model_name>:[version]              Install a model.
  uninstall <model_name>:[version]            Uninstall a model.
  credentials <user>@<domain>                 Set credentials.

Search:
  search <query>                              Search for a model.
  search <query> --include-adult              Search for a model and include adult results.
  search <query> --only-adult                 Search for a model and only include adult results.

Options:
  --install-completion          Install completion for the current shell.
  --show-completion             Show completion for the current shell, to copy it or customize
                                the installation.
  --help                        Show this message and exit.

Run 'aimm help [command]' for more information on a command.
```

[ <a href="https://github.com/visioninit/ai-models-cli">Repository</a> ]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- DESKTOP APP -->
### AIMM GUI

<p align="center">
<img width="500" src="https://user-images.githubusercontent.com/654993/201464617-0e7a4b97-e2b5-45c5-a4d6-69d37345248e.png">
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Mission and Goals -->
### Mission And Goals

The mission is to provide the best user and development experience for retreiving and using AI Models. 

<ul>
  <li>Security Goals</li>
  <ul>
    <li>Hash verification</li>
    <li>File scanning for anomolies</li>
    <li>Check mutability of links (github release vs file on hosting provider)
    <li>Publisher verification</li>
    <ul>
      <li>Phone</li>
      <li>Social Media</li>
      <li>Credit Card verification</li>
      <li>Organization verification</li>
    </ul>
  </ul>
  <li>App Goals</li>
  <ul>
    <li>To be the adjunt to Hugging Face in a way PIP and NPM (where people consume) compliment Github (where people develop)</li>
    <li>Excellent discovery / preview facilities, to understand what a model provides</li>
  </ul>
  <li>Website Goals</li>
  <ul>
    <li>Build to fit existing use cases</li>
    <li>Explore ways to serve organizations</li>
</ul>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Development Roadmap

```

[2022]
 |
[December]
 |
 |- Alpha launch & Announcements
 |- Internationalization [AIMM, AIModels.org]
 |- Automate Model Scans [AIModels.org]
 |- Automate Image Previews [AIModels.org]
 |
[2023]
 |
[January]
 |
 |- More robust interface for user accounts submitions [AIModels.org]
 |- User profiles to show involvement with models [AIModels.org]
 |- User validation options (phone, social media, etc) [AIModels.org]
 |
[Feburary]
 |
 |- Integrate frontend GUI [AIMM]
 |
[Beyond] 
 |
 |-	Registry / Repository services
 |			Host 'white-label' custom repositories
 | 			Offer distribution of site software
 |
 |-	Website (aimodels.org)
 |		Allow users to sell models
 |		Packaging Custom Models (blends)
 |		More tools for model evaluation (like compare)
 *	
```

<!-- CONTACT -->
## Contact

Justin Riddiough - contact@aimodels.org (note, I set it up but didn't enable it before! Oops. If you tried to reach out, please try again)

Personal Link: [https://visioninit.dev](https://visioninit.dev)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
