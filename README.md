# Penetration Testing Checklist

_OWASP-based Web Application Security Testing Checklist._

[![Creative Commons Attribution 4.0 International](https://img.shields.io/badge/license-CC--BY--4.0-blue?style=flat-square)](https://spdx.org/licenses/CC-BY-4.0.html)

## Motivation

Using a text-based format such as markdown for this checklist allows for easier manipulation via common UNIX command line tools such as `awk`, `grep`, and `sed`.

## GitHub Issues Templates

Copy markdown file(s) to the `.github/ISSUE_TEMPLATE/` directory, prepend the following YAML snippet to the front matter, and customize for each template:

```yaml
about: ~
assignees: ~
labels: ~
name: ~
title: ~
```

## Report Generation

```sh
pandoc report.md -o report.pdf
```

## Acknowledgement

Based on [Prathan Phongthiproek's OWASP Testing Checklist](https://github.com/tanprathan/OWASP-Testing-Checklist).

Converted to Markdown via [Kyokomi's excel-to-markdown](https://github.com/kyokomi/excel-to-markdown).

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](COPYING).

## Reference

- [GitHub Help: Configuring issue templates for your repository](https://help.github.com/en/github/building-a-strong-community/configuring-issue-templates-for-your-repository)

- [Pandoc User's Guide: Creating a PDF](https://pandoc.org/MANUAL.html#creating-a-pdf)

## See Also

- [Penetration Testing Guide](https://github.com/oxr463/pentesting-guide)

- [Penetration Testing Virtual Machine](https://github.com/oxr463/pentesting-vm)
