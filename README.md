# tinit - A Linux tiny init process

Almost nothing in this repo is mine. Inspired by the reading of [1], I decided
to follow Thomas Petazzoni's suggestion and create a repo containing a Linux
initialization script suitable for resource-limited systems, which can be reused
in Buildroot as an alternative to the one provided by Busybox.

The script, from which the logo-related part has been removed, is a copy of the
one that was added to Buildroot with commit [2] by Damien Le Moal.

[1] https://lore.kernel.org/buildroot/20230206230203.70e2dbd8@windsurf/T

[2] https://github.com/buildroot/buildroot/commit/6939b5cacf076b0c7e83ad02d13f51b1011adc6f
