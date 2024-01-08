{
  "$schema": "https://mintlify.com/schema.json",
  "name": "CorriereDelloSport.FUN",
  "logo": {
    "dark": "/images/logo_cds.png",
    "light": "/images/logo_cds.png"
  },
  "favicon": "/favicon.svg",
  "colors": {
    "primary": "#E20613",
    "light": "#FF3F4B",
    "dark": "#E20613",
    "anchors": {
      "from": "#E20613",
      "to": "#FF3F4B"
    }
  },
  "topbarLinks": [
    {
      ///RICORDATI DI SISTEMARE QUESTA SEZIONE
      "name": "Assistenza",
      "url": "mailto:hi@mintlify.com"
    }
  ],
  "topbarCtaButton": {
    "name": "Gioco fun",
    "url": "https://corrieredellosport.fun/home"
  },
  "tabs": [
    {
      "name": "Regolamento",
      "url": "regolamento"
    }
  ],
  "anchors": [
    {
      "name": "Pronostici",
      "icon": "book-open-cover",
      "url": "https://corrieredellosport.fun/algoritmo-del-gol"
    },
    {
      "name": "Classifiche",
      "icon": "trophy",
      "url": "https://corrieredellosport.fun/ranking"
    },
    {
      "name": "News",
      "icon": "newspaper",
      "url": "https://corrieredellosport.fun/news"
    }
  ],
  "navigation": [
    {
      "group": "Guida al gioco",
      "pages": ["Introduzione", "Concorso", "Registrazione"]
    },
    {
      ///RICORDATI DI INSERIRE LE ALTRE SEZIONI QUI
      "group": "Essentials",
      "pages": ["essentials/markdown", "essentials/code", "essentials/images", "essentials/settings", "essentials/navigation"]
    },
    {
      "group": "API Documentation",
      "pages": ["api-reference/introduction"]
    },
    {
      "group": "Endpoint Examples",
      "pages": [
        "api-reference/endpoint/get",
        "api-reference/endpoint/create",
        "api-reference/endpoint/delete"
      ]
    }
  ],
  "footerSocials": {
    "twitter": "https://twitter.com/mintlify",
    "github": "https://github.com/mintlify",
    "linkedin": "https://www.linkedin.com/company/mintsearch"
  }
}


---------------

//esempio di dropdown accordion
<AccordionGroup>
  <Accordion icon="github" title="Clone your docs locally">
    During the onboarding process, we created a repository on your Github with
    your docs content. You can find this repository on our
    [dashboard](https://dashboard.mintlify.com). To clone the repository
    locally, follow these
    [instructions](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)
    in your terminal.
  </Accordion>
  <Accordion icon="rectangle-terminal" title="Preview changes">
    Previewing helps you make sure your changes look as intended. We built a
    command line interface to render these changes locally. 1. Install the
    [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the
    documentation changes locally with this command: ``` npm i -g mintlify ```
    2. Run the following command at the root of your documentation (where
    `mint.json` is): ``` mintlify dev ```
  </Accordion>
</AccordionGroup>
