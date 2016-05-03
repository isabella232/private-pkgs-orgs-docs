# Migrating a User Scope to an Org Scope

Many users have already registered an npm user with the @scope they
want to use for their org. If you attempt to register an org with a
scope already in use, and you are already logged in as that user, you
will be prompted to automatically migrate that user to an org.

Once your @scope is owned by an org, **you can no longer log in as
your former username**. Orgs are not users and do not have usernames
and passwords. During migration, you will be prompted to pick a new
username. This new user will have the same password as your old user,
but all packages that belonged to your old user will now belong to the
org. Your new user will have Super-Admin privileges to the org.
