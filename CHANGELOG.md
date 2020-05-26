commit 846ac2db01501a8938669da43a6c64cca0d7d780
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue May 26 09:20:35 2020 -0400

    Fixed Python requirements

commit f40ea9d8e5899e5ee17ee1955b6ca45f625da42b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue May 26 09:12:49 2020 -0400

    Updated CI tests to only test Debian distros

commit 1c325ff456c9020d68a8e63bb5a5e14054404d13
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue May 26 09:12:41 2020 -0400

    Added Ubuntu 20.04 as supported

commit e3c9a10e22b5752f9f30a8d00b991cea1c1e51ea
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue May 26 09:03:56 2020 -0400

    Added new structure based on template
    
    These changes bring this role into alignment with Cookiecutter template.

commit 21f37f03f7c033f9f01ac47a393abaec5cc16148
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue May 26 09:03:09 2020 -0400

    Updated existing files to match template

commit 696ba20ac1adfcebf76961a63f7ef702939791d6
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue May 26 08:50:40 2020 -0400

    Removed old tests in prep of adding new

commit 257a2a8069d5d18233c16f33f67115c760f69f0b
Author: Andreas Piening <apiening@apedv.com>
Date:   Mon May 18 15:39:50 2020 +0200

    Added comment and additional fields to rule-template.

commit 7a8e6cf5ad78f8f87849ab7ff93aa2a0bfc07f66
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 26 12:04:46 2019 -0400

    Create LICENSE

commit 9e93eb605bb0807c5944d7774f4cff01c57062ee
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 26 12:02:43 2019 -0400

    Cleaned up code and resolved install issues
    
    - Closes #15

commit e97077e4fd5920290fc59f12e6473e2aae9a56c9
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 25 23:22:29 2019 -0400

    Cleaned up code structure
    
    - Formatting was not great so I have cleaned it up

commit fa7a4536a03f4eacdc8b7a567031831707303a9a
Author: Christophe Aubry <me@c-aubry.be>
Date:   Tue Jun 12 17:43:27 2018 +0200

    Update main.yml
    
    Remove trailing space

commit 84e83de72b97216275c8fd776e1bb6f2618d1fef
Author: Christophe Aubry <me@c-aubry.be>
Date:   Tue Jun 12 17:40:02 2018 +0200

    Update config_shorewall.yml
    
    Remove trailing space

commit 2035361495701690948ee6ae827a03536f889420
Author: Christophe Aubry <me@c-aubry.be>
Date:   Mon May 28 11:39:13 2018 +0200

    Update main.yml
    
    Add loglevel option

commit 630485d376afc1c762007fd19a14af57e50582ae
Author: Christophe Aubry <me@c-aubry.be>
Date:   Mon May 28 11:35:51 2018 +0200

    Update shorewallv4.conf.j2

commit 69fd22baf7a8c992aa9c228977eb8c0cff711361
Author: Christophe Aubry <me@c-aubry.be>
Date:   Mon May 28 11:35:18 2018 +0200

    Update shorewallv5.conf.j2
    
    Add loglevel configuration

commit 1c0179d75412c7b33b03304557430382d3b0073c
Author: Christophe Aubry <me@c-aubry.be>
Date:   Mon May 28 10:44:09 2018 +0200

    Update main.yml
    
    Add configuration section about Shorewall extra parameters and variables.

commit cb2fb575590c3370ce37e73fc99ba0f42f9db42c
Author: Christophe Aubry <me@c-aubry.be>
Date:   Mon May 28 10:41:47 2018 +0200

    Update config_shorewall.yml
    
    Add section to generate the Shorewall params file.

commit d6b0bf350d0864bff82bde7bbbd252f8fb1cea57
Author: Christophe Aubry <me@c-aubry.be>
Date:   Mon May 28 10:39:06 2018 +0200

    Create params.j2
    
    Add template for the Shorewall params file.

commit ffc7db8493d37d00eb70df9c9d261f2738c45f57
Author: Christophe Aubry <me@c-aubry.be>
Date:   Fri May 25 17:33:32 2018 +0200

    Update main.yml
    
    Add multiples masquerade rules example

commit 5b856a7d8d9cd79e8f52bb71048924c460c6d934
Author: Christophe Aubry <me@c-aubry.be>
Date:   Fri May 25 17:24:57 2018 +0200

    Update masq.j2
    
    Add the capability to generate multiples masquerade rules without breaking the legacy one.

commit 8e669935195d18077c6939ce96f416552941956c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 4 10:57:03 2018 -0400

    Cleaned up tasks
    
    Cleaned up formatting of tasks for more readability and more consistent
    on more recent format of code style.

commit 54d8708306e149967b03b9fb086a6d6aee81baa2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 4 08:15:40 2018 -0400

    Cleaned up variables
    
    The formatting of variable definitions was in need of some serious
    cleanup.

commit 128b7a9b6c6ca608219582fd383826f6c63e211e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 4 01:11:21 2018 -0400

    Updated supported distros

commit e65a59b398a2a2c2edfc57c35cfbfba80a5651e5
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 4 01:11:04 2018 -0400

    Disabled unsupported distros

commit b3edeeabc310fa2bdfd1f525b8d6eb3342e61a5c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 4 01:00:43 2018 -0400

    Implemented Travis CI Testing

commit be2a570246b60f3241cdf09882c293d0e032bcd3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 4 01:00:20 2018 -0400

    Cleaned up formatting based on yamllint

commit 06729e47e22fed60fc832b94748ed3fddfb337b7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 4 00:59:35 2018 -0400

    Cleaned up Galaxy meta info
    
    Cleaned up formatting and etc. based on yamllint

commit 91c612d0bd8ed6758f1da0c6943d6f8ea507f0f6
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 4 00:58:53 2018 -0400

    Added build status

commit ba8b9ee4741d9d0c4afa7c1fe16e99332b06abe2
Author: Sebastien BLAISOT <sebastien@blaisot.org>
Date:   Tue May 1 17:15:26 2018 +0200

    add an option to restart shorewall immediately

commit 4c4be1d4b6bbb4b18c01d96d7a7b3eb72efbc94e
Author: Janne Ojala <janne.ojala@haahtela.fi>
Date:   Mon Feb 26 13:57:38 2018 +0200

    Added support for masq address

commit a8f6c8e617ae574e1ef9b2b087508eb3e41ef797
Author: Sebastien BLAISOT <sebastien.blaisot@cozycloud.cc>
Date:   Tue Feb 20 16:07:10 2018 +0100

    Add default value for add_snat_aliases

commit 9115d28cf8edc0cdad9e193c1448536a9552d4c7
Author: Sebastien BLAISOT <sebastien.blaisot@cozycloud.cc>
Date:   Tue Feb 20 15:56:34 2018 +0100

    add new add_snat_aliases config option to README

commit f568c6e0f3f874b44448331aa737a13d9dfcf7ed
Author: Janne Ojala <janne.ojala@haahtela.fi>
Date:   Tue Feb 20 14:17:57 2018 +0200

    Added support for ADD_SNAT_ALIASES

commit dd44972bd58771247c400dc7207399634219fc10
Author: rbauduin <rbauduin@users.noreply.github.com>
Date:   Thu Jan 12 13:23:44 2017 +0100

    validate config before restart

commit cd19e72faf0c6b293c374f1b6eddf44b76dd5211
Author: rbauduin <rbauduin@users.noreply.github.com>
Date:   Wed Jan 11 11:32:12 2017 +0100

    Added missing "?" before section name

commit 9f5f70e5faa73141d7cadf9e1ad954b306c3fca6
Author: em <eugen.mayer@kontextwork.de>
Date:   Wed Nov 30 13:42:20 2016 +0100

    rename config_shorewall to shorewall_config to have a clear namespace

commit dc9dab8e65b02e3231443be89e9532dcb5840a59
Author: em <eugen.mayer@kontextwork.de>
Date:   Wed Nov 30 13:39:39 2016 +0100

    add docker configuration variable for 5.x

commit c27595477016abee7c6024c40a6338a28a88e52d
Author: em <eugen.mayer@kontextwork.de>
Date:   Wed Nov 30 13:39:04 2016 +0100

    make it compatible to shorewall version 5.x

commit bfc20bcfd88f8540c9ddc5e8c3d97f841e4c73ee
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jun 11 22:11:01 2016 -0400

    Added add'l configuration options
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 5e6ea100b5b798cebc98446670ca20f4f572ed65
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jun 11 16:06:46 2016 -0400

    Added more options
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 6fa2fda0899314b40f1626a3d8787881279fe3b0
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jun 11 15:21:56 2016 -0400

    Updated formatting
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 8519c6e375ec4988db9fd6c6e6ce79858a2f53b7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jun 11 15:18:44 2016 -0400

    Added configuration task
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit c3d5524e3f77ee95c8c223cc82d817d04b8a4380
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jun 11 15:12:59 2016 -0400

    Added var for logs...
    
    The default was /var/log/messages and Ubuntu
    logs are in /var/log/syslog...
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit f34d6491ae1616ccf1a093e9a94b5b39ec6f0511
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jun 9 17:45:43 2016 -0400

    Fixed routing ability and cleaned up vars
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit aa08cd84f9ebd3ef469f076d069bcb9dd5755fa8
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Mon Apr 4 23:02:36 2016 -0400

    first commit
