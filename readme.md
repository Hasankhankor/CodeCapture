[中文](./readme-zh.md)
<h1 align="center">Screenshot to Page</h1>

> **Convert screenshots, image links, or sketches into code using LLM (supporting OpenAi、 Gemini、  Qwen-VL (open-source )) technology, and transform them into web pages with the ability to deploy to the cloud with just one click ☁️.**

+ [Online address](https://screenshot-to-page.vercel.app/) (**Click to experience**, no need to fill in any).

+ PC

<img src="https://cdn.glitch.global/fd139a45-4a65-41b6-9634-41617ab20cdc/1d77437e-2cbd-4329-8228-1da3ec04190a.image.png?v=1703246640297" width="40%" align="center" /><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;➡️&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img src="https://cdn.glitch.global/fd139a45-4a65-41b6-9634-41617ab20cdc/9335be07-579b-4a10-bc2b-bbccd8269f92.image.png?v=1703246494577" width="40%" align="center" />
+ Mobile




## Deployment 🪤
### Docker
```sh
docker run -p  3000:3000 jadenxiong/screenshot-to-page
```
### Vercel
+ Click the button on the right to start deployment: [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/import?s=https%3A%2F%2Fgithub.com%2FMrxyy%2Fscreenshot-to-page&hasTrialAvailable=1&showOptionalTeamCreation=false&project-name=screenshot-to-page&framework=nextjs&totalProjects=1&remainingProjects=1&env=OPENAI_API_KEY)
+ Once deployed, you can start using it;
+ (Optional) [Bind a custom domain](https://vercel.com/docs/concepts/projects/domains/add-a-domain): The DNS of the domain assigned by Vercel is polluted in some regions, binding a custom domain will allow direct connection.
 
## Developers 💪
```sh
# pnpm
pnpm i;
pnpm dev;
```
```sh
# yarn
yarn;
yarn dev;
```
