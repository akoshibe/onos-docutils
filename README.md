onos-docutils
=============

This is a collection of complementary utilities for maintaining the ONOS
Documentation Library.

These scripts can be used to generate content, or information useful for
generating content for, some of the ONOS Guide appendices.

onos-docutils currently contains the following:

 * cli2doc:  collects ONOS CLI commands into wiki-formatted file (see Appendix A :
             CLI commands)

 * src2tree: generates wiki-formatted lists for project names, descriptions,
             and project bundle names (see Appendix C : Source Tree
             Organization)

 * src2rest: scrapes JAX-RS -related code from source, collecting path and
             various parameter information into a single file as reference 
             (see Appendix B : REST API)

 * util2doc: scrapes ONOS utility scripts, collecting each script's
             descriptions, usage information, and potential arguments that they
             take, into a single file for reference (see Appendix A : List of
             ONOS Utility Scripts)

Each script comes with its own usage information displayed by the -h option.

Like ONOS itself, these scripts are technically licensed under Apache v2.0.
