.. .. meta::
   :description: Part 5 of a set of learning exercises meant for exploring Hasura in detail. This part covers using the data API along with SQL views & relationships.
   :keywords: hasura, getting started, step 5, SQL views and relationships

===============================
Part V: Build a blog engine app
===============================

Let's build a simple clone of the popular publishing platform `medium <https://medium.com/>`_ and use that to learn about the features provided by the Hasura platform. Our clone, called ``ether`` will have the following features:

#. Anyone can register on the site
#. Users can publish posts, like and comment
#. Anyone can view published posts, overall likes and comments


Hasura features
---------------

To make this simple application, these are the Hasura features we'll use:

#. Exploring the user & authentication Hasura APIs
#. Creating tables (on postgres) using the ``api-console`` UI
#. Exploring the hasura data APIs as an ``admin``
#. Adding permissions and access control on the data models
#. Adding relationships between the data models
#. Adding aggregations & views to compute derived information (eg: total likes)

Next: User & authentication APIs
--------------------------------

Next, let's head to :doc:`User & authentication APIs <6-user-model>`.
