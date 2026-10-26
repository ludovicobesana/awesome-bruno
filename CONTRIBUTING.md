# Contributing to Awesome Bruno

Thank you for helping keep this list useful for Bruno users. By participating, you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## Suggesting a resource

Before opening a pull request, search the README and open issues to avoid duplicate submissions. A resource should be:

- Directly relevant to Bruno and useful to API developers, QA engineers, or automation teams.
- Publicly accessible, reasonably maintained, and described accurately.
- Placed in the most relevant README category.
- Distinct from resources already listed; explain the different value when a similar link exists.

Please do not submit affiliate links, unrelated promotion, link farms, or resources whose primary value is marketing.

## Opening a pull request

1. Fork the repository and create a focused branch.
2. Add one concise entry in alphabetical order where practical, using this format:

   ```markdown
   - [Resource name](https://example.com) - Clear, factual description.
   ```

3. Check that the URL works, the title matches the destination, and the resource is in the correct category.
4. Run the available local checks:

   ```sh
   # Install once with Homebrew or Cargo:
   # brew install lychee
   # cargo install lychee --locked
   npx -y awesome-lint README.md
   lychee --config .lychee.toml README.md CONTRIBUTING.md CODE_OF_CONDUCT.md
   ```

5. Open a focused pull request explaining what you added, changed, or removed and why.

Maintainers review submissions for relevance, availability, clarity, placement, and duplication. They may request changes or decline a link that does not meet these criteria.
