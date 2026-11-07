# mukul.app

Personal website for Mukul Sharma, served by GitHub Pages at https://mukul.app.

- `site/` is the published folder: a single static page, the resume PDF, and the `CNAME` file for the custom domain.
- The resume PDF comes from `~/dev/generated-docs/resume-build/build_resume_ai_1_0.py --web`, which leaves out the phone number.
- `.github/workflows/pages.yml` publishes `site/` on every push to `main`.
