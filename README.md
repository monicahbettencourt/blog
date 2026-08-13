# Monica H. Bettencourt - Tech Blog 

Personal technical blog where I document the learning process for my career pivot from Operating Room Nursing to DevOps. 

**Live at:** [monicahbettencourt.com](https://monicahbettencourt.com) 

## Technologies

- **Static Site Generator:** Hugo 
- **Theme:** PaperMod
- **Hosting:** Cloudflare
- **Version Control:** Git / GitHub  

## Local Development 

- Create new post: ```hugo new content /content/posts/[post-title.md]```
- Edit frontmatter and add content with Vim: ```vim content/posts/[post-title.md]```
- Start development server: ```hugo server``` 
- Build for production: ```hugo build```
- Deployment:
	- Add file to staging area: ```git add [post-title.md]```
	- Commit changes to local repository: ```git commit -m "[commit message]"```
	- Push to remote GitHub repository: ```git push```
	- Cloudflare auto-deploys from main branch

## Project Standards

This project follows the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification for all commits made after August 10, 2026.

**Commit Format:** 

```<type>(<scope>): <subject>```

**Commit Types:**

- `feat`: New feature (e.g., new blog posts)
- `fix`: Bug fixes and typos
- `docs`: Documentation updates
- `refactor`: Restructuring code or content
- `chore`: Configuration changes

**Note:** Earlier commits used informal messages as this standard was adopted recently.
