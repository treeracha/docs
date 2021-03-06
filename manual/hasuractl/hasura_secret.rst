.. _hasura_secret:

hasura secret
-------------

Add, delete and manage secrets on a Hasura cluster. Sometimes you want to use some secret key or a token such as an API key or a client secret. It is not always a good idea to push these secret keys to a git repository or write them explicitly in your code. Using Hasura you can have your secrets safe in the cluster, and access them whenever you want.

Synopsis
~~~~~~~~


Create, update, delete secrets on a hasura cluster

Options
~~~~~~~

::

  -h, --help   help for secret

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --project string   hasura project directory where the commands should be executed. (default: current directory)

SEE ALSO
~~~~~~~~

* :ref:`hasura <hasura>` 	 - hasura controls the hasura project
* :ref:`hasura secret list <hasura_secret_list>` 	 - List secrets from a cluster
* :ref:`hasura secret update <hasura_secret_update>` 	 - Update secret for a key

*Auto generated by spf13/cobra on 3-Jan-2018*
