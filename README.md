RoadToBetterCrafting
====================

Ressources, articles, subjects, themes that would help crafting better applications

# SOLID and OO Design
  
maintainability is about how the code is resilient to change
is this code easy to change?  
design by contract  
tell don't ask  
http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod  

##ruby
http://rubyrogues.com/rr-60-solid-with-jim-weirich/  
http://blog.groupbuddies.com/posts/16-dependency-injection  
  
http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod

####code
https://github.com/jimweirich/presentation_solid_ruby  
http://selfless-singleton.rickwinfrey.com/2012/12/03/building-solid-foundations-of-oop/  
http://www.sitepoint.com/solid-ruby-dependency-inversion-principle/  
  
# Testing
##rspec
http://www.neo.com/2013/12/20/custom-failure-messages-in-rspec-given  
test by level  
tests give feedback on the design
integrations tests are a scam  
build a safe zone with unit tests and only use integration tests at the boundaries with vendor libs  
functionnal tests / acceptance tests  
mutation tests  
fuzzy tests

# Design By Contract
http://en.wikipedia.org/wiki/Design_by_contract
  
# Design Patterns / AntiPatterns / Refactoring
http://sourcemaking.com/
  
# Mistakes  
fix it now
find the root cause of the bug not the symptom  
covers it with a unit tests  
  
# after
is this code easy to change? -> should be thought in design
http://saikuro.rubyforge.org/  
benchmarks
https://github.com/MiniProfiler/rack-mini-profiler
https://github.com/tmm1/rblineprof
check sql queries done underneath    
  
# notes  
Command/Query Separation 

---
# DevOps  
http://www.cyberciti.biz/faq/what-process-has-open-linux-port/
  
#Databases
##choose the right index
* https://tomafro.net/tags/using-indexes-in-rails
* http://rny.io/rails/postgresql/2013/08/20/postgresql-indexing-in-rails.html
