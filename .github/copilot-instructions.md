# Copilot Instructions

## Project Overview

This project is a Flutter application designed to be:

* Maintainable
* Scalable
* Secure
* Easy to onboard for new developers

All generated code must follow these instructions.

NO expliques nada. Solo implementa y avisa cuando acabes
---

## Architecture Principles

Follow:

* SOLID
* Separation of Concerns
* DRY
* KISS

Avoid unnecessary complexity.

Prefer explicit and readable solutions.

---

## Folder Structure

Respect the existing project structure.

Reusable widgets:

lib/shared/widgets/

Constants:

lib/shared/constants/

Styles:

lib/shared/styles/

Extensions:

lib/shared/extensions/

Utilities:

lib/shared/utils/

Services:

lib/shared/services/

Feature models:

lib/features/<feature>/domain/models/

Repositories:

lib/features/<feature>/data/repositories/

Screens:

lib/features/<feature>/presentation/screens/

Feature widgets:

lib/features/<feature>/presentation/widgets/

---

## Flutter Guidelines

Prefer StatelessWidget whenever possible.

Use const constructors whenever possible.

Avoid widgets larger than 250 lines.

Extract reusable widgets.

Avoid deeply nested widget trees.

Avoid business logic inside widgets.

Avoid calculations inside build().

Keep UI and business logic separated.

---

## State Management

Use the existing project solution.

Priority:

1. Riverpod
2. Bloc
3. Provider

Do not introduce new state management libraries.

---

## Code Quality

Always use strong typing.

Avoid dynamic unless absolutely necessary.

Avoid duplicated code.

Prefer composition over inheritance.

Keep methods small and focused.

Prefer named parameters.

Prefer immutable objects.

Document non-obvious business rules.

---

## Security

Never hardcode:

* Secrets
* Tokens
* Credentials
* API Keys

Validate all user input.

Avoid exposing internal errors.

Avoid logging sensitive information.

---

## Performance

Use pagination for large datasets.

Avoid unnecessary rebuilds.

Use lazy loading where appropriate.

Prefer const widgets.

Avoid expensive synchronous operations on the UI thread.


---

## Copilot Response Rules

DO NOT explain your reasoning, just inform when you finish

Generate only what is required.

Avoid unrelated code generation.

Do not analyze the entire project unless explicitly requested.

Request missing files when needed.

Work only with the provided context.
