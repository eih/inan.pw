# inan.pw

This is a hugo geenrated website. Feel free to browse the code and get bits you
like and modify as you wish.

## How to run

You'll have to install Hugo ^0.68.1/extended Clone the repository and change
into the directory. Run `hugo serve` to run a local copy. `hugo` command builds
and puts everything into `public` directory.

**Note:** There are some static files like GPG keys that you might want to
remove before you decide to use this repo.

## TODO

Currently Netlify can't build the website as this needs the extended version of
Hugo. Only workaround is to commit `resources/*` directory, which is usually not
commited. Once Netlify solves this issue, that directory should be added back to
`.gitignore` file.