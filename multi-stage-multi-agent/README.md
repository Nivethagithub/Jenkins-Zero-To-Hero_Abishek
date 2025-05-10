# Multi Stage Multi Agent

Set up a multi stage jenkins pipeline where each stage is run on a unique agent. This is a very useful approach when you have multi language application
or application that has conflicting dependencies.

We can use different agent for frontend, backend (DB) ; instead of defining one common agent.. Containers will be created based on the defined requirement.
