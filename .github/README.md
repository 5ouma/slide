<h1 align="center">Slide</h1>

<div align="center">

**🎦 Presentation as Code**

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/5ouma/slide?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/5ouma/slide?style=flat-square)
[![GitHub last commit](https://img.shields.io/github/last-commit/5ouma/slide?style=flat-square)](https://github.com/5ouma/slide/commit/HEAD)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/m/5ouma/slide?style=flat-square)](https://github.com/5ouma/slide/commits/main)
<br />
[![Deploy](https://img.shields.io/github/actions/workflow/status/5ouma/slide/deploy.yml?label=deploy&style=flat-square)](https://github.com/5ouma/slide/actions/workflows/deploy.yml)
[![pre-commit](https://img.shields.io/github/actions/workflow/status/5ouma/slide/pre-commit.yml?label=pre-commit&style=flat-square)](https://github.com/5ouma/slide/actions/workflows/pre-commit.yml)

</div>

<br /><br />

## 📝 Writing a New Slide

1. Create a new directory in the `/src` with the name of the slide

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
