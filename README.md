<h3 align="center">
  GraphCMS Examples
</h3>

<p align="center">
  Example projects to help you get started with GraphCMS
</p>

## Links

[Join our Slack](https://slack.graphcms.com)</li> &middot; [Read the Docs](https://graphcms.com/docs) &middot; [Learn more about GraphCMS](https://graphcms.com)

## Examples

### GraphCMS Features & Recipes

Examples demonstrating how to use GraphCMS features.

| Features                               | Description                                                                                                                                                                                                                                        | Demo                                         |
| -------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- |
| [Using Asset Upload](using-asset-upload)     | Programmatically upload assets using the [Asset Upload endpoint](https://graphcms.com/docs/content-api/assets#uploading-assets)                                                                                                                          |                                              |
| [Using Management SDK](using-management-sdk)     | Basic [Management SDK](https://www.npmjs.com/package/@graphcms/management) script to create a schema with [Remote Fields](https://graphcms.com/docs/schema/field-types#remote) to query data directly from the [Stripe API](https://stripe.com/docs/api)                                       |      |
| [Using Mutations](using-mutations)     | [Next.js](https://nextjs.org) app demonstrating how to use GraphCMS mutations with [`graphql-request`](https://github.com/prisma-labs/graphql-request), [`SWR`](https://github.com/zeit/swr) and API routes                                        | https://graphcms-using-mutations.now.sh      |
| [Using Pagination](using-pagintion)    | [Next.js](https://nextjs.org) app demonstrating how to paginate GraphCMS queries with [`graphql-request`](https://github.com/prisma-labs/graphql-request)                                                                                          | https://graphcms-using-pagination.vercel.app |
| [Using Union Types](using-union-types) | A basic product marketing site using union types to compose UI 'blocks' with components. Built with [Next.js](https://nextjs.org), [`graphql-request`](https://github.com/prisma-labs/graphql-request) and [Tailwind CSS](https://tailwindcss.com) | https://graphcms-using-union-types.now.sh    |

### Frameworks & Libraries

Examples demonstrating how to use GraphCMS with popular application frameworks.

| Frameworks & Libraries                                           | Description                                                                                                                                                                                                                                                      | Demo                                                       |
| ---------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| [Algolia](with-algolia)                                          | Sync content to Algolia via webhooks on publish using Next.js API routes.                                                                                                                                                                                        | https://graphcms-with-algolia.vercel.app                   |
| [Apollo Client 3](with-apollo-client-3)                          | Using [Apollo Client 3](https://www.apollographql.com/docs/react) to query data from GraphCMS.                                                                                                                                                           | https://graphcms-with-apollo-client-3.vercel.app           |
| [Apollo Server](with-apollo-server)                              | Using [`apollo-datasource-graphql`](https://github.com/poetic/apollo-datasource-graphql) to pull a GraphCMS schema into an existing [Apollo Server](https://www.apollographql.com/docs/apollo-server/)                                                           | https://graphcms-with-apollo-server.herokuapp.com          |
| [Express](with-express)                                          | A simple [Express](https://expressjs.com/) app using `ejs` templating and [`awesome-graphql-client`](https://github.com/lynxtaa/awesome-graphql-client)                                                                                                          | https://graphcms-with-express.herokuapp.com                | A basic [Gatsby](https://www.gatsbyjs.org/) site that uses [`gatsby-source-graphcms`](https://github.com/GraphCMS/gatsby-source-graphcms) to build product pages with data from GraphCMS |
| [Gatsby](with-gatsby)                                            | A basic [Gatsby](https://www.gatsbyjs.org/) site that uses [`gatsby-source-graphcms`](https://github.com/GraphCMS/gatsby-source-graphcms) to build product pages with data from GraphCMS                                                                         | https://graphcms-with-gatsby.now.sh                        |
| [Gatsby (File System Route API)](with-gatsby-filesystem-routing) | A basic [Gatsby](https://www.gatsbyjs.org/) site that uses [`gatsby-source-graphcms`](https://github.com/GraphCMS/gatsby-source-graphcms) to build product pages using Gatsby's [File System Route API](https://www.gatsbyjs.com/docs/file-system-page-creation) | https://graphcms-with-gatsby-filesystem-routing.vercel.app |
| [Gatsby Image](with-gatsby-image)                                | How to use [`gatsby-image`](https://www.gatsbyjs.org/packages/gatsby-image/) with GraphCMS assets                                                                                                                                                                | https://graphcms-with-gatsby-image.now.sh                  |
| [GraphCMS Image](with-graphcms-image)                            | How to use [`graphcms-image`](https://github.com/GraphCMS/graphcms-image) with Gatsby                                                                                                                                                                            | https://graphcms-with-graphcms-image.now.sh                |
| [GraphQL Codegen](with-graphql-codegen) | Automatically generated types for your GraphCMS project with [GraphQL Code Generator](https://graphql-code-generator.com/docs/getting-started/index) | https://graphcms-with-graphql-codegen.vercel.app |
| [Gridsome](with-gridsome)                                        | A basic example using `gridsome create` CLI and [`@gridsome/source-graphql`](https://www.npmjs.com/package/@gridsome/source-graphql)                                                                                                                             | https://graphcms-with-gridsome.now.sh                      |
| [MDX (with Gatsby)](with-gatsby-mdx)                                | How to use [`gatsby-plugin-mdx`](https://www.gatsbyjs.com/plugins/gatsby-plugin-mdx) with `RichText` fields from GraphCMS.                                                                                                                                                                | https://graphcms-with-gatsby-mdx.vercel.app                  |
| [MDX (with Next.js)](with-nextjs-mdx-remote)                     | This example demonstrates how to use markdown fields from GraphCMS with `MDX` in Next.js                                                                                                                                                                         | https://graphcms-with-nextjs-mdx-remote.vercel.app         |
| [Next.js](with-nextjs)                                           | A basic [Next.js](https://nextjs.org) application, featuring `getStaticProps` and `getStaticPaths` to build static product pages                                                                                                                                 | https://graphcms-with-nextjs.now.sh                        |
| [Next.js i18n Routing](with-nextjs-i18n-routing)                 | How to use [Next.js Internationalized Routing](https://nextjs.org/docs/advanced-features/i18n-routing) with GraphCMS content                                                                                                                                     | https://graphcms-with-nextjs-i18n-routing.vercel.app       |
| [Next.js Image](with-nextjs-image)                               | How to use [Next.js Image Component](https://nextjs.org/docs/api-reference/next/image) with GraphCMS assets                                                                                                                                                      | https://graphcms-with-nextjs-image.vercel.app              |
| [Next.js Image with Custom Loader](with-nextjs-image-loader)                               | How to use a [custom loader](https://nextjs.org/docs/api-reference/next/image#loader) function with [Next.js Image Component](https://nextjs.org/docs/api-reference/next/image) and GraphCMS assets                                                                                                                                                      | https://graphcms-with-nextjs-image-loader.vercel.app              |
| [Nuxt.js](with-nuxtjs)                                           | A simple Nuxt.js starter using `create-nuxt-app` CLI with Tailwind and Axios added                                                                                                                                                                               | https://graphcms-with-nuxtjs.now.sh                        |
| [React.js](with-reactjs)                                         | This example demonstrates how to query from GraphCMS with graphql-request in React.js                                                                                                                                                                            | https://graphcms-with-reactjs.now.sh                       |
| [Vue.js](with-vuejs)                                             | A vanilla Vue.js starter using `vue create` CLI with Vue Router                                                                                                                                                                                                  | https://graphcms-with-vuejs.now.sh                         |
| [Sapper](with-sapper)                                            | A SeveltJs example using Sapper                                                                                                                                                                                                                                  | https://graphcms-with-sapper.now.sh                        |

### Built by the community

| Name                                                                                | Author |
| ----------------------------------------------------------------------------------- | ------ |
| [Next.js 9 and Zeit Now Boilerplate](https://github.com/UnlyEd/next-right-now/)     | UnlyEd |
| [Cache Boilerplate](https://github.com/UnlyEd/GraphCMS-cache-boilerplate)           | UnlyEd |
| [Next Admin Backoffice Boilerplate](https://github.com/UnlyEd/next-right-now-admin) | UnlyEd |
| [Simple shopping cart using GridSome]( https://github.com/Dunebook/gridsome )       | Deven  |

If you have created any examples with GraphCMS and want to see them featured here, reach out via our on-site chat on [graphcms.com](https://graphcms.com)!
