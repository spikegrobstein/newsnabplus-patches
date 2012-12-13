# newsnab+ patches

These patches are for the newsnab+ package.

apply them with:

    patch -d path/to/nnplus -p1 -b -i patch_name.patch

## Patches

### nzb_check_permissions.patch

This patches the NZB object so it checks permissions before creating the lettered directory
and before writing the NZB file itself. Without this patch, `nnplus` prints a warning to the
console, marks the NZB as being written and moves on.

## Notes

newsnab+ is a commercial product with a commercial licence. This is only
to be used on that version of the software.
