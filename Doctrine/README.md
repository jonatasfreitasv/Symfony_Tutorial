
### Doctrine
##### New entity
<code>php app/console doctrine:generate:entity</code>

##### Import existing database
<code>php app/console doctrine:mapping:import AppBundle annotation</code>

##### Generate geter and setters
<code>php app/console doctrine:generate:entities AppBundle/Entity/</code>

##### Clear Cache
<code>php app/console doctrine:cache:clear-metadata</code>

<code>php app/console doctrine:cache:clear-query</code>

<code>php app/console doctrine:cache:clear-result</code>

##### Update Database Schema
<code>php app/console doctrine:schema:update --force</code>
