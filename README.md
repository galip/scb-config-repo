# scb-config-repo

Centralized configuration repository for Spring Cloud Bus demo.

## Structure

- application.yml  
  Global shared configuration.

- campaign-service.yml  
  Campaign domain configuration.

- feature-flags.yml  
  Runtime feature toggles propagated via Spring Cloud Bus.

## Usage

scb-config-server will use this repo as file config.
