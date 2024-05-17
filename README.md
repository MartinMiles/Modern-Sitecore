# Modern-Sitecore

[<img src="https://github.com/MartinMiles/awesome-sitecore/raw/master/sitecore-logo.png" align="right" width="80">](https://sitecore.com)

> A curated list of helpful blog posts to take you through the complexities of modern Sitecore implementations. Please contribute!

This repository features the most valuable curated links to the community posts helping you with modern Sitecore development
Contributions welcome. Add links through pull requests or create an issue to start a discussion.

## Contents

- [Experience Edge](#experience-edge)
- [GraphQL](#graphql)
- [Storybook](#storybook)
- [Vercel](#vercel)

> Please note, **Modern Sitecore** list only classifies and reviews useful GitHub repositories you may benefit from. 
>
> If you're looking for a more comprehensive list of articles, blog posts, videos, and Q'n'A please refer to the [Sitecore Link](https://Sitecore.Link) knowledge base.

## Experience Edge

- [Tuning Guide for Sitecore Experience Edge GraphQL](https://sitecorerap.wordpress.com/2023/03/02/tuning-guide-for-sitecore-experience-edge-graphql) - Edge has a hard limit of 80 requests per second, and despite Edge caches graphQL queries, this cache is cleared after any publish, so we must tune it and enable ISR correctly.

## GraphQL

- [Extend Sitecore Layout Query to Eliminate XMC Customizations And Extra GraphQL Requests](https://sitecorerap.wordpress.com/2024/04/25/extend-sitecore-layout-query-to-eliminate-xmc-customizations-and-extra-graphql-requests) - Shows how to use GraphQL to get rid of unwanted requests by combining desired data (say page breadcrumb) along with `rendered` section under `item` output of layout data coming from Edge.

- ## Storybook

- [Fix Storybook React Hook Errors on Sitecore JSS 21.6.0 and Up](https://www.getfishtank.com/blog/fix-storybook-react-hook-errors-on-sitecore-jss) - Shows how to fix React hook errors when running Storybook in Headless SDK 21.6 and newer by patching `compilerOptions.paths.react` section of `tsconfig.json`.


## Vercel

- [Vercel Server Caching - Faster Sitecore Builds, Less Network Chatter]([https://github.com/Sitecore/Sitecore-Azure-Quickstart-Templates](https://sitecorerap.wordpress.com/2024/02/27/vercel-server-caching-faster-sitecore-builds-less-network-chatter)) - How to debug Vercel and implement caching with Memory-Cache.

