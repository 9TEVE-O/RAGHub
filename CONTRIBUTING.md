# Contribution Guidelines

Thank you for your interest in contributing to **RAGHub**. This project is intended to be a useful public directory for the RAG ecosystem.

RAGHub is a curated directory, not an endorsement list, benchmark, security review, or production-readiness assessment.

## How to Contribute

We welcome contributions from everyone. If you'd like to add a new framework, project, or resource, follow these steps to get started:

1. **Fork this repository**.
2. **Create a new branch**: Use a descriptive name for your branch. For example: `git checkout -b add-framework-yourname`.
3. **Make your changes**: Update the appropriate section in the `README.md` by following the table format below.
4. **Update the Table of Contents (TOC)**: If you are adding a new category or section, make sure to add a link to the TOC.
5. **Submit a pull request (PR)**: Once your changes are complete, submit a PR to the main branch for review.

## Inclusion Criteria

A listed resource should have at least one of the following:

- a public website or documentation page
- a public GitHub repository
- clear relevance to retrieval, indexing, embeddings, reranking, document parsing, document intelligence, evaluation, observability, guardrails, provenance, or RAG application development
- enough public information for readers to understand what the resource does

## Exclusion Criteria

Please do not add resources that are:

- unrelated to RAG, retrieval, indexing, document processing, evaluation, or adjacent infrastructure
- impossible to verify from public sources
- primarily spam, affiliate bait, or lead-capture with no useful technical detail
- presented with unsupported claims such as "best", "most accurate", "enterprise-ready", or "production-proven" unless a reliable source is supplied
- copied from vendor marketing text without neutral rewriting

## Contribution Format

### Adding a new resource: frameworks, projects, services, papers, or sites

If you're adding a resource, please insert a new row into the correct category table in the README.md file, using the following format:

```md
| Framework Name | Description (max 80 char where practical) | Website link | Github link | Github stars | Last activity on Github |
```

Example:

```md
| LangChain | A framework for building applications with LLMs. | [Website](https://langchain.com) | [Github](https://github.com/langchain-ai/langchain) | 93.2k | 9h ago |
```

If you don't see a category that fits your resource, feel free to create a new category by adding it both to the README.md and updating the Table of Contents accordingly.

## Description Standards

Descriptions should be:

- factual
- neutral
- concise
- written in plain technical language
- free from unsupported superlatives
- clear about whether the resource is a framework, engine, hosted service, evaluation tool, paper, or tutorial

Avoid descriptions that imply maintainers have validated, endorsed, audited, or benchmarked a resource unless that review has actually happened and is linked.

## Metadata and Activity

GitHub stars, activity labels, pricing, licence status, hosted availability, and product scope can change quickly.

Before submitting a PR, contributors should:

1. Check that website links resolve.
2. Check that GitHub links point to the correct repository or organisation.
3. Verify that the resource is still active enough to be useful.
4. Avoid stale activity labels where the date cannot be verified.
5. Use `-` or `--` when a field is unknown rather than guessing.

## Updating the Table of Contents (TOC)

If you're adding a new category or section, please ensure that you update the Table of Contents to reflect your changes. Use the following format to add new categories:

```md
- [New Category Name](#new-category-name)
```

For example, if you're adding a new section called RAG Best Practices, add it like this in the TOC:

```md
- [RAG Best Practices](#rag-best-practices)
```

## Provenance and Attribution

Preserve existing licence notices and attribution. Repository ownership, a fork, or a copy is not proof of original authorship.

See [PROVENANCE.md](PROVENANCE.md) for the current provenance and attribution boundary for this repository.

## Final Steps

Once you've added your contribution, please:

1. Ensure that your changes follow the format provided and are consistent with the current style.
2. Double-check that all links work and point to the correct URLs.
3. Remove unsupported endorsement, benchmark, security, or production-readiness claims.
4. Submit your pull request.

Thank you again for contributing to **RAGHub**. Your help makes this a more useful resource for everyone exploring the RAG ecosystem.
