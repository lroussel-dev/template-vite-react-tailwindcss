# Vite + React + TailwindCSS

This is a template to create quick little project with

- **Vite**
- **React**
- **React Router Dom**
- **TailwindCSS**

## Installation :

```bash
mkdir project-name

cd project-name

# Copy the template 
git clone https://github.com/lroussel-dev/template-vite-react-tailwindcss.git .

# Remove the actual git project
rm -R .git

# Init your brand new git project
git init

# Et voilà !
```

## NGINX Docker

You can run easely your Vite Build with nginx.

### Config docker

```bash
# Edit the docker config
nano docker-compose.yml 
```

#### container_name

Change at `container_name: nginx-server` by your project name.

#### port

Change at `port: 8080:80`.

## Run the docker

```bash
# Create the build with vite
npm run build

# Run the docker!
docker compose up -d
```
