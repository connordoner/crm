# ADR 5: Split contacts into types

Date: 26 November 2023

## Status

Accepted

## Context

I need to split my contacts into types so that different types of contact can have different attributes and behave differently.

## Decision

I'll split my contacts into three types: people, organisations and pets. In broad terms, they'll be as follows:

* A person will be anybody who I know or have known (for example, those who've died)
* An organisation will be any group of people with a shared purpose, such as a company, charity or campaign group
* A pet will be an animal kept by a person

## Consequences

* I'll need to consider how changes to my `Contact` model impact individual types of contacts
