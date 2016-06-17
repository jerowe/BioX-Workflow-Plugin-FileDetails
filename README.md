# NAME

BioX::Workflow::Plugin::FileDetails - Get metadata for files in directories
processed by [BioX::Workflow](https://metacpan.org/pod/BioX::Workflow)

# SYNOPSIS

List your plugins in your workflow.yml file

    ---
    plugins:
        - FileDetails
    global:
        - indir: /home/user/gemini
        - outdir: /home/user/gemini/gemini-wrapper
        - file_rule: (.vcf)$|(.vcf.gz)$
        - infile:
    #So On and So Forth

# DESCRIPTION

BioX::Workflow::Plugin::FileDetails is a plugin for [BioX::Workflow](https://metacpan.org/pod/BioX::Workflow). It gets
metadata for files in directories processed by [BioX::Workflow](https://metacpan.org/pod/BioX::Workflow) including MD5,
size, human readable size, date created, last accessed, and last modified.

# AUTHOR

Jillian Rowe <jillian.e.rowe@gmail.com>

# Acknowledgements

This modules continuing development is supported by NYU Abu Dhabi in the Center for Genomics and Systems Biology.
With approval from NYUAD, this information was generalized and put on bitbucket, for which
the authors would like to express their gratitude.

# COPYRIGHT

Copyright 2015- Jillian Rowe

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO
