=========================
heroku-private-buildpacks
=========================
This supports simplified loading buildpacks from a private git repository / repositories.

It hooks in only to the ``compile`` stage of each buildpack.

Requires ``custom-ssh-key-buildpack`` or similar.

Add ``.heroku-private-buildpacks`` file in the project root:

.. code::

    git@github.com:user1/private-repo1
    git@github.com:user2/private-repo2
    # ...
