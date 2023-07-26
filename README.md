# dremio-oss-test-image

This is the Dremio OSS imaage with default dremio user turned on, this is useful in testing and cuts down the need to include this dremio.conf manually on every invokations 


## Why?

I got tired of adding the default test user for every application I built for dremio that needed to really test against a dremio service. Finally when I tried to setup a service in a github action this proved to be super challenging. So here we are. This solves a test automation problem well and cuts out some startup friction for other projects.
