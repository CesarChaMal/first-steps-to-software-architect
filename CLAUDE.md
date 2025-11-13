# CLAUDE.md - AI Assistant Guide

## Repository Overview

**Repository Name**: first-steps-to-software-architect
**Type**: Educational Documentation Repository
**Primary Purpose**: Curated learning roadmap for aspiring Software Architects
**Language**: Markdown (English)
**License**: MIT (2018)

### What This Repository Is

This is a **pure documentation repository** containing no executable code. It serves as a structured collection of educational video references (primarily YouTube) organized by software architecture topics. The repository provides a learning path from foundational concepts to advanced architectural patterns.

### What This Repository Is NOT

- Not an application with source code
- Not a library or framework
- Not a project requiring builds, tests, or deployments
- Not a repository with configuration files or dependencies

---

## Repository Structure

```
/home/user/first-steps-to-software-architect/
├── readme.md          # Main documentation (7KB) - All educational content
├── LICENSE            # MIT License (1KB)
├── CLAUDE.md          # This file - AI assistant guide
└── .git/              # Git metadata
```

### Key Files

| File | Purpose | Size | Format |
|------|---------|------|--------|
| `readme.md` | Complete learning resource catalog | 7,048 bytes | Markdown |
| `LICENSE` | MIT License terms | 1,057 bytes | Plain text |
| `CLAUDE.md` | AI assistant documentation | Variable | Markdown |

**Absolute Path**: `/home/user/first-steps-to-software-architect/`

---

## Content Organization

The `readme.md` file is organized into **8 major learning categories**:

### 1. Basics (4 videos)
Foundational topics: Agile, Modern Development Practices, Non-Functional Requirements, DevOps

### 2. Microservices (20 videos)
Comprehensive coverage of:
- Introduction and best practices
- 12 Factors App
- Differences from SOA
- Key concepts: Service Discovery, Fault Tolerance, Monitoring, Scaling
- Infrastructure: API Gateway, Centralized Logging/Configuration
- Architecture patterns: Event-driven, Eventual Consistency

### 3. Designing REST API (1 playlist)
RESTful service design principles and best practices

### 4. Software Design (10 videos)
- Design patterns
- SOLID principles
- Abstraction and simplicity
- Cohesion
- TDD and Functional Programming

### 5. Code Quality (14 videos)
Quality metrics and practices:
- Technical debt, refactoring, legacy code
- Code coverage, complexity, duplication
- Code smells and coding standards
- Static analysis and code reviews

### 6. Architecture (10 videos)
Architectural patterns and principles:
- Layered architecture
- Vertical slices
- Separation of concerns
- Modularity and security
- Asynchronous communication
- Non-functional requirements

### 7. Web Application Security (1 video)
OWASP Top 10 security flaws overview

### 8. 5 Minute Introductions - Tools and Terminology (9 videos)
Quick intros to Spring ecosystem and Maven:
- Spring Framework, Boot, Cloud, Data, Batch
- Spring Initializr and Data REST
- Web Services and Maven

---

## Documentation Conventions

### Content Structure Standards

1. **Hierarchy**:
   - Main title: `# How to become a Software Architect?`
   - Section title: `# References`
   - Category headers: Plain text (e.g., "Basics", "Microservices")
   - Video entries: Bulleted lists with links

2. **Link Formatting**:
   - **Inconsistent format** across the document:
     - Some use markdown links: `[Title](URL)`
     - Others use plain text with hyphen: `Title - URL`
   - **Preferred format**: Markdown links `[Title](URL)` for better readability

3. **URL Patterns**:
   - YouTube single videos: `https://www.youtube.com/watch?v={VIDEO_ID}`
   - YouTube playlists: `https://www.youtube.com/playlist?list={PLAYLIST_ID}`
   - All links are external (no internal references)

4. **Title Conventions**:
   - Descriptive and self-explanatory
   - Often question-based (e.g., "What is...", "Why should...")
   - Include category prefix for clarity (e.g., "Microservices - ", "Code Quality - ")

### Formatting Inconsistencies to Note

The current document has mixed formatting:
- Lines 5-9: Plain text format `Title - URL`
- Lines 12-31: Markdown format `[Title](URL)`
- Lines 44-46, 49-52: Plain text format `Title - URL` or `Title : URL`

**Recommendation**: Standardize to markdown format throughout for consistency.

---

## Development Workflow

### Common Tasks

#### 1. Adding New Video References

```markdown
## Category Name
- [Descriptive Title](https://www.youtube.com/watch?v=VIDEO_ID)
```

**Process**:
1. Read `readme.md` to understand current structure
2. Identify appropriate category or create new one
3. Add entry in consistent markdown format
4. Ensure title is descriptive and follows naming conventions
5. Verify URL is valid and accessible

#### 2. Organizing Content

**Principles**:
- Group related topics together
- Maintain logical progression (basics → advanced)
- Use category headers to separate topics
- Keep entries within categories sorted logically (not alphabetically)

#### 3. Creating New Categories

**When to create**:
- New architectural domain not covered (e.g., "Event Sourcing", "CQRS")
- Sufficient content (3+ videos) to warrant separate section
- Distinct from existing categories

**Format**:
```markdown

Category Name
- [First Video Title](URL)
- [Second Video Title](URL)
```

#### 4. Standardizing Links

**Convert from**:
```markdown
Title - https://www.youtube.com/watch?v=VIDEO_ID
```

**To**:
```markdown
- [Title](https://www.youtube.com/watch?v=VIDEO_ID)
```

---

## Git Workflow

### Branch Strategy

**Main Development Branch**:
- Claude tasks: `claude/claude-md-mhy321g1iiuij3xx-01NsBewFwuGEW2ZREKyWEafV`

### Commit Conventions

**Commit Message Style** (based on repository history):
- Simple, descriptive messages
- Examples: "Update readme.md", "Create readme.md"
- Focus on what changed, not why (documentation changes are self-explanatory)

**Recommended Format**:
```
Add [Category]: [Number] new video references

- [Specific changes if needed]
```

Examples:
- `Add Microservices: 3 new videos on monitoring`
- `Standardize link formatting in Software Design section`
- `Create new category: Event-Driven Architecture`

### Git Operations

**Committing Changes**:
```bash
git add readme.md
git commit -m "Update readme.md with new microservices resources"
```

**Pushing Changes**:
```bash
git push -u origin claude/claude-md-mhy321g1iiuij3xx-01NsBewFwuGEW2ZREKyWEafV
```

**Important**: Always push to the designated Claude branch, not main/master.

---

## Quality Standards

### Documentation Quality

1. **Accuracy**:
   - Verify all URLs are accessible
   - Ensure titles accurately reflect video content
   - Check for broken links regularly

2. **Completeness**:
   - Each entry should have a title and URL
   - Titles should be descriptive enough to understand content without clicking
   - All categories should have at least one entry

3. **Consistency**:
   - Use consistent link format (markdown preferred)
   - Follow category naming conventions
   - Maintain consistent spacing between sections

4. **Organization**:
   - Logical grouping of related topics
   - Clear category separation
   - Progressive difficulty where applicable

### Link Validation

**Before committing**, verify:
- URLs are properly formatted
- Links point to valid YouTube resources
- No duplicate entries within categories
- Markdown syntax is correct

---

## AI Assistant Guidelines

### When Working with This Repository

1. **No Code Execution**: This repository has no code to run, test, or build
2. **Focus on Content**: All work involves editing `readme.md`
3. **Preserve Structure**: Maintain the established categorical organization
4. **Link Quality**: Prioritize accurate, accessible YouTube links
5. **Format Consistency**: Standardize to markdown link format

### Common Requests and How to Handle Them

#### "Add new resources about [topic]"
1. Search for appropriate category in `readme.md`
2. Add entries in markdown format
3. Ensure titles are descriptive
4. Commit with clear message

#### "Organize/restructure the content"
1. Read entire `readme.md` to understand current state
2. Identify logical groupings
3. Propose reorganization to user before implementing
4. Update while preserving all existing links

#### "Check for broken links"
1. Extract all URLs from `readme.md`
2. Inform user that manual verification is needed (no automated link checker available)
3. Provide list of URLs for user to verify

#### "Standardize the formatting"
1. Read `readme.md` completely
2. Identify inconsistencies (plain text vs markdown links)
3. Convert all to markdown format: `[Title](URL)`
4. Verify no content is lost in conversion

### What NOT to Do

- Do not add build files (package.json, etc.) - not needed
- Do not create source code directories - wrong repository type
- Do not add CI/CD configurations - no builds to run
- Do not create test files - no code to test
- Do not modify the LICENSE file without explicit user request
- Do not remove existing content without user confirmation

---

## Repository Metadata

### Git Information

**Current Branch**: `claude/claude-md-mhy321g1iiuij3xx-01NsBewFwuGEW2ZREKyWEafV`
**Remote Origin**: `http://local_proxy@127.0.0.1:24572/git/CesarChaMal/first-steps-to-software-architect`

**Commit History**:
```
ddaa243 - Update readme.md (latest)
196ec8a - Create readme.md
fe97e51 - Initial commit
```

**Total Files**: 2 (excluding .git/)
**Total Size**: ~8KB
**Creation Date**: 2018 (based on LICENSE)
**Last Modified**: November 13, 2023

### Technology Stack

**Languages**: Markdown
**Dependencies**: None
**Build Tools**: None
**Frameworks**: None
**Testing**: None

---

## Extending This Repository

### Potential Improvements

1. **Link Format Standardization**:
   - Convert all plain text links to markdown format
   - Improves readability and consistency

2. **Category Expansion**:
   - Event Sourcing and CQRS
   - Domain-Driven Design (DDD)
   - Serverless Architecture
   - Container Orchestration (Kubernetes)
   - Database Architecture Patterns

3. **Enhanced Organization**:
   - Add difficulty indicators (Beginner/Intermediate/Advanced)
   - Include video duration estimates
   - Add brief descriptions for each video
   - Create table of contents with anchor links

4. **Additional Resources**:
   - Books and articles
   - Interactive courses
   - Architecture diagrams
   - Practice exercises

5. **Metadata Addition**:
   - Publication dates for videos
   - Speaker/channel information
   - Related resources cross-references

### Implementation Considerations

**Before adding new features**:
- Maintain backward compatibility with existing structure
- Keep the repository simple and focused on documentation
- Avoid over-engineering (no complex tooling needed)
- Ensure all additions provide clear value to learners

---

## Troubleshooting

### Common Issues

**Issue**: Links appear broken or inaccessible
**Solution**: YouTube links may be region-restricted or removed. Verify manually and replace if needed.

**Issue**: Formatting looks inconsistent
**Solution**: Use markdown linter or preview to check formatting before committing.

**Issue**: Duplicate entries
**Solution**: Search the entire document before adding new links.

**Issue**: Git push fails
**Solution**: Ensure branch name starts with 'claude/' and ends with session ID.

---

## Quick Reference

### File Paths
- README: `/home/user/first-steps-to-software-architect/readme.md`
- LICENSE: `/home/user/first-steps-to-software-architect/LICENSE`
- This guide: `/home/user/first-steps-to-software-architect/CLAUDE.md`

### Editing Workflow
1. Read `readme.md` to understand current state
2. Make changes using Edit tool
3. Verify changes maintain formatting consistency
4. Commit with descriptive message
5. Push to designated Claude branch

### Link Format Template
```markdown
- [Descriptive Title](https://www.youtube.com/watch?v=VIDEO_ID)
```

### Category Header Template
```markdown

Category Name
- [Video 1](URL)
- [Video 2](URL)
```

---

## Summary

This repository is a **learning resource catalog** for software architecture education. It's intentionally minimal, containing only curated video references organized by topic. All AI assistant work should focus on:

1. Maintaining and improving documentation quality
2. Adding valuable educational resources
3. Ensuring formatting consistency
4. Preserving the simple, accessible structure

The repository requires no builds, tests, or deployments - only thoughtful curation and organization of educational content.

---

**Last Updated**: 2025-11-13
**Document Version**: 1.0
**Maintained by**: AI Assistants working with this repository
