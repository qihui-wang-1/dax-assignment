# Exercise: Evaluating a Document Parsing Pipeline

**No code required. AI tools are fine to use. Log the prompt if used.**

## Context

We have a document parsing pipeline that parses financial documents like presentations and reports into markdown and json at a scale of thousands of documents per week. Example downstream use cases include search and question answering (RAG) over the filings, NER (Named Entity Recognition) for knowledge graph or entity linking, financial metrics extraction, and segment analysis. The parsing solution relies on an external service, so we need a reliable way to know how good the parsing results actually are at scale, and whether a given output is good enough for downstream services to use.

This is close to real work you'd do in the role. We care mostly about how you think and approach problems.

## What you get

(Attached separately)

- source_file.pdf: a real financial document that we parsed.
- parsed.json and parsed.md: parsed output in json and md for the source pdf.

It's a long document and the output is long too. You're not expected to read all of it. Skim to get a feel for the variety and the scale, since both shape how you'd evaluate quality. The json output contains the parsed content for each element in md, as well as other metadata such as element type, location information, etc. So the md file can always be generated from the json file.

## The task

Put together an initial plan for how you'd measure the quality of the parsing results, and where you'd start. A short note on how this could grow in the long term is good to have, but the plan only needs to focus on the scope of 1-2 people for the first 2-4 weeks on English documents. You can base the evaluation solution on either the md or json file that you think makes the most sense.

Also list the questions you'd need answered if there are any, along with the assumptions you make.


## What to send

Keep the plan around 1 page in any format. Pseudocode or a sketch of a scoring function is welcome if it helps, but it's optional and we won't evaluate it as code. Also log the prompt if any AI tool is used.
