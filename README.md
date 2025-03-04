# Cursor Rules for Supabase Development

A collection of coding guidelines and best practices for Supabase development, designed to be used with the Cursor IDE.

## Overview

This repository contains a set of rules that help maintain consistent coding standards when working with Supabase projects. These rules are automatically applied by Cursor IDE when working with relevant files, providing real-time guidance and ensuring code quality.

## Included Rules

- **SQL Formatting** - Guidelines for writing clean, consistent Postgres SQL
- **Database Migrations** - Best practices for creating and managing database migrations
- **Database Functions** - Standards for implementing Postgres/Supabase database functions
- **Row Level Security Policies** - Guidelines for implementing secure RLS policies
- **Edge Functions** - Best practices for writing Supabase Edge Functions with Deno/TypeScript
- **Next.js with Supabase Auth** - Implementation guidelines for authentication in Next.js applications

## Usage

1. Clone this repository
2. The rules are located in the `.cursor/rules` directory
3. When working with Supabase projects in Cursor IDE, these rules will be automatically applied to relevant files based on their glob patterns

## Rule Application

Each rule file includes:
- A description of its purpose
- File glob patterns that determine when the rule is applied
- Detailed guidelines and best practices
- Code examples and anti-patterns to avoid

## License

This project is licensed under [CC0 1.0 Universal](LICENSE) - see the LICENSE file for details.

## Credits

These rules are adapted from the official [Supabase examples and prompts](https://github.com/supabase/supabase/blob/master/examples/prompts/). 