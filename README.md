# Symfony 2 Tutorial

### Check
#####  Security
<code>php app/console security:check</code>

##### Routes
<code>php app/console router:debug</code>

-

### Generate
##### New bundle
<code>php app/console generate:bundle</code>

##### New controller
<code>php app/console generate:controller</code>

-

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
