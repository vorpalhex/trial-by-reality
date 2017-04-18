# trial-by-reality
> Sample data ranging from naive to difficult but real examples designed to thoroughly test and stress email, names, and other real life data

## Using

Data is stored in JSON format with an extremely consistent format (the exception being of course, the JSON trials by themselves). In Node, importing your desired trial is as simple as requiring it. Most other languages can import JSON natively.

## Contributing

Please fork, create a new branch, add your cases and open a PR back to this repo. New types of data are always welcome, as are unique cases for existing types.

## Licensing

This is licensed under the very permissive MIT. Please feel free to use, modify, etc. this repo as suits your purposes.

## FAQ

### My Phone/Email/Social Security/Etc ended up in this data!

Oh dear! That shouldn't happen ever, but open a bug report immediately.

### Your trial 'X' isn't a real case!

While there's a chance you are right, you are quite likely encountering an oddball but correct case. Please check the reference comments in the data, or failing that, the linked background document. If neither of those point to an RFC definition, or you otherwise think you are still right, you can open a bug.

### How good is good enough? Do I need to pass ALL the trials?

You should pass all the trials. Often times the only action needed is to relax validation. By not accepting valid entries you are automatically preventing valid users from using your system. Even if a case isn't common today, it's likely common in the near future.
