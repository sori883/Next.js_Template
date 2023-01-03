This is a [Next.js](https://nextjs.org/) project template.

## Usage
1. Create new Repository from [this template](https://github.com/sori883/Next.js_Template/generate)

1. Git Clone 

1. Rename env.local.example to env.local

1. Execute the following commands
```
$ yarn install
$ yarn dev 
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Includes
- emotion
- mui
  - see: sec/mui
- next-head-seo
  - see: src/components/nonVisual/siteHead
- storybook
  - see: .storybook
- husky
  - added eslint
- pathpida
- next-sitemap
  - see: next-sitemap.config.js

## env
- APP_URL
  - Used for these
    - next.config.js
    - src/components/nonVisual/siteHead
    - next-sitemap.config.js