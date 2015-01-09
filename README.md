# turf-owners

`npm owner` management for Turfjs npm modules.

# install

    npm install -g ownership

# usage

Provides two utilities:

## ownership

`ownership`: takes one argument, the name of the package,
and adds all users to that package as owners. For instance:

    ownership express

Would add all users in `example-users.json` as owners to the
`express` packages.

## ownership-all

`ownership-all` doesn't take any arguments: it adds all users in
`example-users.json` to all packages in `example-packages.json`.
