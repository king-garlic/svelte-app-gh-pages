# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm init svelte

# create a new project in my-app
npm init svelte my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.






# 프로젝트 세팅 - Skeleton project
    
    C:\job\front-end\svelte>npm init svelte svelte-app-gh-pages

    create-svelte version 2.0.0-next.135

    Welcome to SvelteKit!

    This is beta software; expect bugs and missing features.

    Problems? Open an issue on https://github.com/sveltejs/kit/issues if none exists already.

    √ Which Svelte app template? » Skeleton project
    √ Add type checking? » None
    √ Add ESLint for code linting? ... No / Yes
    √ Add Prettier for code formatting? ... No / Yes
    √ Add Playwright for browser testing? ... No / Yes

    Your project is ready!
    ✔ ESLint
    https://github.com/sveltejs/eslint-plugin-svelte3
    ✔ Prettier
    https://prettier.io/docs/en/options.html
    https://github.com/sveltejs/prettier-plugin-svelte#options
    ✔ Playwright
    https://playwright.dev

    Install community-maintained integrations:
    https://github.com/svelte-add/svelte-adders

    Next steps:
    1: cd svelte-app-gh-pages
    2: npm install (or pnpm install, etc)
    3: git init && git add -A && git commit -m "Initial commit" (optional)
    4: npm run dev -- --open

    To close the dev server, hit Ctrl-C

    Stuck? Visit us at https://svelte.dev/chat


    C:\job\front-end\svelte>cd svelte-app-gh-pages

    C:\job\front-end\svelte\svelte-app-gh-pages>code .




# 프로젝트 세팅 - 모듈설치 - npm install
    C:\job\front-end\svelte\svelte-app-gh-pages>npm install

        > svelte-app-gh-pages@0.0.1 prepare
        > svelte-kit sync


        added 137 packages, and audited 138 packages in 1m

        20 packages are looking for funding
        run `npm fund` for details

        found 0 vulnerabilities

        C:\job\front-end\svelte\svelte-app-gh-pages>



# 프로젝트 세팅 - 로컬 개발 서버 실행 - npm run dev
    C:\job\front-end\svelte\svelte-app-gh-pages>npm run dev

    > svelte-app-gh-pages@0.0.1 dev
    > svelte-kit dev


    SvelteKit v1.0.0-next.330

    network: not exposed
    local:   http://localhost:3000

    Use --host to expose server to other devices on this network


    
# 프로젝트 세팅 - 소스 공유 - 리포지토리 생성
    echo "# svelte-app-gh-pages" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/king-garlic/svelte-app-gh-pages.git
    git push -u origin main


# 프로젝트 세팅 - Building - npm run build"# svelte-app-gh-pages" 
