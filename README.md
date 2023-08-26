# React + TypeScript + Vite

Template from [here](https://github.com/tailwindtoolbox/Landing-Page/blob/master/index.html).

## Requirements

For our developer setup we have assumed Ubuntu 22.04 as our base OS.

## Description

A simple setup using:

- Vite ( build tool)
- TypeScript (build tool)
- React (UI)
- Tailwind CSS (UI)
- Example of the project file structure

## Setup

1. Navigate to a location on your file system you'd like to put this project and clone this repository and run:

```bash
git clone https://github.com/kensonjohnson/relativepath.tech.git
```

2. `cd` into the `relativepath.tech` directory:

```bash
cd ./relativepath.tech
```

3. Run the `setup.sh` bash script to make sure your system has necessary requirements:

```bash
bash setup.sh
```

4. Run `test.sh` bash script to test the server out locally:

```bash
bash test.sh
```

5. If you see a `200 OK` response back, congrats! Open your browser and head over to `http://localhost:5173` to take a peak at the site.

## In Progress

- `build.sh` script for local build automation
- `test.sh` script for local testing automation
- We need a `token` or `ssh-key` to actually deploy the site to GitHub Pages
- After we have a working GH Pages pipeline, swap branch in `cicd.yaml` to trigger on push or pull request to "main"
- Add a badge for CICD status visibility
- Add badges for requirements visibility
