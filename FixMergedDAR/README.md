# FixMergedDAR
Regenerates DAR Conditions files for plugins that have been merged using ZMerge.

ZMerge always alters the plugin name containing formIDs referenced, and depending on the merge
may also alter the Form ID. This patcher generates a new set of _conditions.txt files for 
affected plugins and forms. The output files should be loaded using a separate mod that overrides
the default files.
