# amplify-adapter-customized
Thanks to Gustavo Zimbron(https://github.com/gzimbron) for the base library

[Adapter](https://kit.svelte.dev/docs/adapters) for SvelteKit apps to Amplify Host CI/CD.


Limitations:

- Artifacts size limit: 200 MB
- Upload file size limit: 50 MB

## Video tutorial

[![SvelteKit + Amplify CI/CD](./readme_assets/video.jpg)](https://youtu.be/YGgJgq2LLpE)

### Official documentation on AWS Amplify

[https://docs.aws.amazon.com/amplify/latest/userguide/get-started-sveltekit.html](https://docs.aws.amazon.com/amplify/latest/userguide/get-started-sveltekit.html)

## Sveltekit amplify adapter installation

- Install with npm, pnpm or yarn:

```bash
npm install --save-dev amplify-adapter-customized
```

- Add the adapter to your `svelte.config.js`:

```js
// svelte.config.js
import adapter from 'amplify-adapter-customized';
```

## Amplify Hosting Integration (CI/CD)

## License

[MIT](LICENSE)
