# connorpmullins.github.io

My personal website

## Local Development

To run this site locally:

1. Make sure you have Ruby installed (the site uses Ruby 3.3.4)
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Start the local development server:
   ```bash
   bundle exec jekyll serve
   ```
4. Visit `http://localhost:4000` in your browser

The site will automatically rebuild when you make changes to your files. You can stop the server at any time by pressing `Ctrl+C` in the terminal.

### Troubleshooting

If you see an error about port 4000 being in use, you can either:

- Stop any existing Jekyll server processes
- Or specify a different port:
  ```bash
  bundle exec jekyll serve --port 4001
  ```
