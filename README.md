# Melle van der Brugge - Personal Resume

This is my personal resume website built using the [Jekyll Resume Template](https://github.com/jglovier/resume-template) by Joel Glovier.

## About Me

I recently completed the Master's in Artificial Intelligence at the University of Amsterdam, focusing on mathematics, programming, and a broad range of AI techniques. My academic work culminated in a thesis on assessing image quality in photoacoustic imaging, combining both classic image quality metrics and modern deep learning approaches.

## Website Structure

- `_config.yml`: Main configuration file with personal information
- `_data/`: YAML files containing resume data (education, projects, skills, etc.)
- `_layouts/resume.html`: Main layout template
- `images/avatar.jpg`: Profile picture

## Customization

To customize this resume:

1. Edit `_config.yml` for basic information (name, title, contact info, social links)
2. Update files in `_data/` directory:
   - `education.yml`: Educational background
   - `projects.yml`: Projects and research work
   - `skills.yml`: Technical skills and expertise
   - `interests.yml`: Personal interests and activities
   - `links.yml`: Additional links and resources

## Deployment

This site is configured for GitHub Pages deployment. Simply push changes to the main branch and the site will be automatically built and deployed.

## Local Development

To run locally (requires Ruby and Jekyll):

```bash
bundle install
bundle exec jekyll serve
```

Or using Docker:

```bash
docker image build -t resume-template .
docker run --rm --name resume-template -v "$PWD":/home/app --network host resume-template
```

Then visit `localhost:4000` in your browser.

---

© 2024 Melle van der Brugge
