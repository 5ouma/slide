<h1 align="center">Slide</h1>

<div align="center">

**🎦 Presentation as Code**

<br />

[![CI](https://img.shields.io/github/actions/workflow/status/5ouma/slide/ci.yml?label=CI&style=flat-square)](https://github.com/5ouma/slide/actions/workflows/ci.yml)
[![Deploy](https://img.shields.io/github/actions/workflow/status/5ouma/slide/deploy.yml?label=Deploy&style=flat-square)](https://github.com/5ouma/slide/actions/workflows/deploy.yml)
[![pre-commit](https://img.shields.io/github/actions/workflow/status/5ouma/slide/pre-commit.yml?label=pre-commit&style=flat-square)](https://github.com/5ouma/slide/actions/workflows/pre-commit.yml)

![Repobeats Analytics Image](https://repobeats.axiom.co/api/embed/e046fa1f10173e062d5a00919a80acfd88394415.svg)

</div>

<br /><br />

## 📝 Writing a New Slide

1. Create a new directory in the `/src/slides` with the name of the slide

2. Create a new `index.md` file in the created directory

3. Copy the YAML front matter from the `template.yml` file

4. Build the slide

   ```sh
   bun run build
   ```

<br /><br />

## 🔨 Development

1. Clone this repository

   ```sh
   git clone https://github.com/5ouma/slide.git
   ```

2. Run the development server

   ```sh
   bun run dev
   ```
