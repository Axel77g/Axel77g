### Hi there 👋

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=axel77g&count_private=true&theme=github_dark&show_icons=true)

**Stack**  

<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/react/react.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/express/express.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/php/php.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/56a826d05cf762b2b50ecbe7d492a839b04f3fbf/topics/laravel/laravel.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/vue/vue.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mysql/mysql.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/postgresql/postgresql.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/docker/docker.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/cb661bc288627f05a5ac4187b00495fd8048c9fa/topics/heroku/heroku.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/3c66f1237835e0b877190fbea528d0ebece7bccf/topics/vercel/vercel.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png"></code>

name: Bug Report
description: Something went awry
labels: ["type: bug"]
body:
  - type: markdown
    attributes:
      value: |
        Need help or support?
        Please don't open an issue! Head to https://stackoverflow.com/questions/tagged/chart.js.
  
  - type: markdown
    attributes:
      value: "Bug reports MUST be submitted with an interactive example: https://codepen.io/leelenaleee/pen/WNyJXEe."

  - type: markdown
    attributes:
      value: Chart.js versions lower then 4.x are NOT supported anymore, new issues will be disregarded.

  - type: textarea
    attributes:
      label: Expected behavior
      description: Tell us what should happen.
    validations:
      required: true

  - type: textarea
    attributes:
      label: Current behavior
      description: Tell us what happens instead of the expected behavior.
    validations:
      required: true

  - type: input
    attributes:
      label: Reproducible sample
      description: |
        Please provide issue reproduction.
        You can use [this codepen](https://codepen.io/leelenaleee/pen/WNyJXEe) to make a reproducible sample.

        Major framework wrappers for chart.js templates:
        [vue-chart-3 sandbox (Vue)](https://codesandbox.io/s/vue-chart-3-chart-js-issue-template-bpg7k?file=/src/App.vue)
        [ng2-charts sandbox (Angular)](https://codesandbox.io/s/ng2charts-chart-js-issue-template-fhezt?file=/src/app/app.component.ts)
        [react-chartjs-2 sandbox (React)](https://codesandbox.io/p/sandbox/react-chartjs-2-chart-js-issue-template-v4-forked-lqz5tn?file=%2Fsrc%2FApp.tsx)

        For typescript issues you can make use of [this TS Playground](https://www.typescriptlang.org/play?#code/JYWwDg9gTgLgBAbzgYQBYENZwL5wGZQQhwDkAxhrAHQBWAziQNwCwAUGwG6ZxkwAecALxwAJhDIBXEAFMAdjCoBzaTACiAG2kz5AIQCeASREAKAEQg9aTDFMBKOOjpwAEgBUAsgBlk6WVzoaWnIwLKxcUHAWVljCstIA7iiUMMa8fAA0iGxwOXAwemDSAFyk6sBxJOnZuSLoMOglCNW5ueroAEbS6nQlANqmAErSIqaZpjrqEtKjcKYAml3qEPEzpgDiUNJyqwAKElBgmqsA8lC+yqYAulWsLS219XQqPXC9Tbd3n22d6iUkAMRwCB4OAANQgMGkDBun0+DwarwAjAAmTKIgCcmQAzJkAKyZVFwLHXZp3bCXUnYGG5CBgGDACCyF7vT50MjoTTM0ktPiNbl3fk5KmCuB6PkfWFwEXYfkyiU4NjYWyMIA) to make a reproducible sample.

        If filing a bug against `master`, you may reference the latest code via
        https://www.chartjs.org/dist/master/chart.umd.js (changing the filename to
        point at the file you need as appropriate). Do not rely on these files for
        production purposes as they may be removed at any time.
    validations:
      required: true
  
  - type: textarea
    attributes:
      label: Optional extra steps/info to reproduce

  - type: textarea
    attributes:
      label: Possible solution
      description: If you have suggestions on a fix for the bug.

  - type: textarea
    attributes:
      label: Context
      description: |
        How has this issue affected you? What are you trying to accomplish?
        Providing context helps us come up with a solution that is most useful in the real world.

  - type: input
    attributes:
      label: chart.js version
      description: Which version of `chart.js` are you using?
      placeholder: "v0.0.0"
    validations:
      required: true

  - type: input
    attributes:
      label: Browser name and version

  - type: input
    attributes:
      label: Link to your project
