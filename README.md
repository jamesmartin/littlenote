# Little Note

Like a diary, but simpler.

## Use

Thought of something? Write it down:

```
$ littlenote

# $EDITOR opens on a new date/time-stamped file
# Write down your thoughts...
```

Put notes in their place:

```
$ littlenote -d ~/some/place/for/notes/
```

## Configure

Optionally, configuration lives in a YAML file called `$HOME/.littlenote`:

```yaml
directory: /Users/foo/some/place/for/notes
```

## Other Commands

You can easily see the content of all of today's notes:

```
$ littlenote show
# all today's notes are paged through less
# ...
```

Or see older notes by passing a query parameter in the form `number` `unit`
(without a space):

```
$ littlenote show 3d
# See notes from the last 3 days

$ littlenote show 2w
# See notes from the last 14 days

$ littlenote show 1m
# See notes from the last 31 days

$ littlenote show 1y
# See notes from the last 365 days
```

You can get a list of the file paths of all notes within a given date range:

```
$ littlenote list
# List of all files written today

$ littlenote 365d
# List of all files written in the last 365 days

$ littlenote 5w
# List of all files written in the last 5 weeks

$ littenote 9m
# List of all files written in the last 9 months

$ littenote 10y
# List of all files written in the last 10 years
```
