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

You can easily see all of today's notes:

```
$ littlenote show
# all today's notes are paged through less
# ...
```
