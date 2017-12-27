# United States Forest Service Online Permitting


[![FS ePermits Badge](https://img.shields.io/badge/-ePermit-006227.svg?colorA=FFC526&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAMAAAAolt3jAAACFlBMVEUAAAD%2F%2FyXsvSW8qiXLsCXjuSXyvyX7wiX2wSXqvCXUsyXBrCXvviX%2F%2FyX8yCWUmyVliSV%2FkyV7kSWIlyV0jiWZnSX9yCXNsSXRsiXWtCVWgyVYhCXZtiX%2FyCV8kiV%2BkiX%2FyiX%2FzCWIliWElSX%2FzSX2wiVniSV3kCX2wiXUtCU5eCVujCXWtCW%2FqyXDrSWtpCWwpSWmoiWypiXeuCWJlyWPmSXiuiX%2F1CXsvSXFriW4qSWrpCWElCVdhiWSmiW3qCXCrSXQsiXyvyX%2F1CX%2F%2FyP%2F5yX%2F0iX%2FxCXrvCX%2FxiX%2F0iX%2F5yUcbCU6eCVAeiUfbiVEfCVEfCVZhCVEfCUzdSUtcyVAeyVNfyVZhCVGfSVEfCUqciUSaSUIZCUYayWPmSUUaiUCYiUVaiU1diVjiCUjcCVNfyVFfCXnuyU%2FeiUqciVliSVPgCWQmSUlcCVQgSV7kSX%2FxiWHliVPgCWPmSUtcyWLlyUibyVXgyWzpyX%2FxyXJryUXayVahCWIliWOmCU4eCV2jyXBrCXcuCXMsSVbhSUYaiV1jyU4eCVOgCVujCU6eCUudCWAkyUlcCVEfCVehiVYhCU%2FeiVvjSUSaSUAYiUAYiU1diWAlCUxdSUAYSUBYiUTaSVvjSVqiyVGfSUcbCUQaCUPaCUNZyULZiURaSUYayU6eCVehiVehiV1jyVmiSVOgCVRgSVSgSV2jyVxjSVvjSVMulUvAAAATHRSTlMAAGrao3NYUFdvndVtADfb%2Ffn2%2BP3cOMHAl%2F39lT7v7jsx6eozTPT2UoT%2B%2F4%2FGz%2FL46ut68%2FJ4B1Kau9Pu%2F%2BzQt5NMBgAKGUikQxYIJokgEwAAAFtJREFUCNdjZGBEBiwMvIy2jIcZGRkZrRiPMTIyiFsiJPcxMkgyOsJ4OxhZGFgYOeE6SeMyMuhGI0yew8LAxI3gMqFxGRmMGUthvBZGRgZzFEczMDC4QJlbGRgA3KAIv74V5FUAAAAASUVORK5CYII%3D)](README.md)

### A collection of documents and links related to the 18F Acqusition Forest Service ePermitting project

## Welcome!

The U.S. Forest Service is engaged in an ongoing effort to modernize and simplify their permitting processes. One facet of this effort is to make them available to obtain and purchase online. GSA's 18F Acquisition is working with the Forest Service to plan and build out this platform.

## Opportunity statement

#### The opportunity statement = the problem we are trying to solve with the ePermitting project

Existing administrative systems *restrict, rather than facilitate,* responsible use of the forest, and reduce the time spent on stewardship-oriented business and engaging Forest users. These processes and systems result in *low customer satisfaction, less business, and less of a connection* between people and their environment. We believe that by *digitizing these processes for the public,* we will allow Forest Service staff to focus on their primary job, and promote facilitation. And, we believe that this will lead to *better customer satisfaction and more permits.*

## Project code repositories and sites

We welcome you to explore, make suggestions, and contribute to our code.

 - [Project principles, timelines and key documents](https://github.com/18F/fs-online-permitting/wiki/Introduction): these pages describe the work done so far with links to key documents.

- [Development site](forest-service-epermit.app.cloud.gov): a live version of our vendors' latest work

    - [Code repository](https://github.com/18F/fs-permit-platform) 
    - [User stories and other requirements for christmas tree permits](https://github.com/18F/bpa-fs-xmas-trees/blob/master/docs/RFQ.md#user-stories-for-front-end-layer)
    - [User stories and other requirements for special use applications](https://github.com/18F/bpa-fs-epermit-intake) 

- [Middlelayer API](https://fs-middlelayer-api.app.cloud.gov/): an application protocol interface (API) that that simplifies communication between the development site (above) and Forest Service backend system (NRM SUDS)
    - [Code repository](https://github.com/18F/fs-middlelayer-api) 
    - [User stories and other requirements](https://github.com/18F/bpa-fs-epermit-api) 
    - [Schemas describing how ePermitting fields match SUDS fields](https://github.com/18F/fs-permit-api-schemas)
    
- [Proposed and potential major components of the system](https://github.com/18F/fs-online-permitting/blob/master/docs/modules.pdf)     

## Discovery research

Prior to our initial build, we researched the processes that will need to be brought online by our system.

- [FS prototype](https://github.com/18F/forest-service-prototype) This repository includes user research conducted by 18F/TTS
    - [Discovery plan](https://github.com/18F/forest-service-prototype/blob/develop/docs/discovery-plan.pdf)
    - [Special Uses workshop readout](https://github.com/18F/forest-service-prototype/blob/develop/docs/special-uses-read-out.pdf)
    - [Christmas tree workshop readout](https://github.com/18F/forest-service-prototype/blob/develop/docs/christmas-tree-read-out.pdf)
    -  [Christmas tree Permitting Options](https://github.com/18F/fs-online-permitting/blob/xmas-tree-discovery/docs/christmas-tree-permitting-options.pdf)
    - [Round 1 UX findings](https://github.com/18F/forest-service-prototype/blob/develop/docs/round1-findings-reccomendations.pdf)
