# MuzHack Blog
Source Ghost package for the MuzHack blog. Use Buster to generate the deployed, static blog.

## Development
To write a new blog post, do the following:
1. Select the right node version: `nvm use`.
2. Start the dev server as follows: `npm start`.
3. Visit http://localhost:2368 and write and publish a new post.
4. Publish the post online:
  1. Run `buster generate`.
  2. Enter buster's output directory: `cd static`.
  3. Commit your changes: `git commit`.
  4. Push your changes to GitHub: `git push`.
