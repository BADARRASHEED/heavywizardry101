# Heavy Wizardry 101 Official Repo

This is the official Repo for the book: Heavy Wizardry 101. You can find all the source code of the book organised by chapters

## Requirements

You need to install docker in your machine in order to install the development environment.

## Development Environment

The repository includes a Dockerfile that can be used to create a docker image with all the required images.

To create the image execute:

```bash
$ ./build.sh
```

Once the image is created you can access the development environment running

```bash
export MSYS_NO_PATHCONV=1
```

and then the script

```bash
start_env.sh
```

or you can use the shortcut command

```bash
export MSYS_NO_PATHCONV=1 && ./start_env.sh
```

_NOTE: Execute the script from the repo root directory. The script makes all the source code available inside the docker container as a volume_

## Author

**Badar Rasheed Butt**  
AI Engineer | Azure Specialist
