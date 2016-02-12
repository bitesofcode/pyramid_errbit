pyramid_errbit
======================

The `pyramid_errbit` project is aimed at providing an integration layer between the
errbit reporting system and the pyramid web framework, using the errbit-reporter python package.

Installation
-----------------------

    pip install pyramid_errbit

Usage
-----------------------

Inside your pyramid configuration file, just add the following parameters:

    include=
        pyramid_errbit
    
    # errbit configuration information
    errbit.api_key=12345
    errbit.url=http://my.errbit.com
    errbit.project_root=''
    errbit.environment_name=''
    errbit.server_name=''

License
------------------------

MIT license