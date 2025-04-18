# Awesome PDF [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated community driven list of awesome PDF (Portable Document Format) libraries, services and datasets. Both open source and commercial services are included and accepted.

When working with PDF files, you sometimes come across great services, libraries, or interesting tools that you want to remember. Here is our list.
From parsers for extracting text, images, and tables, to automated PDF creation and processing, to accessibility and compliance. AI included!



## Contents

- [Parsers, OCR and extraction](#parsers-ocr-and-extraction) services and libraries. If you need to extract something from PDFs look here.
- [Creation and production](#creation-and-production) - Need to produce PDF, here some of the cool libraries and services
- [Readers and viewers](#readers-and-viewers) - Need to show PDF in your app or site, maybe here you can find something.
- [Accessibility](#accessibility) - Accessibility and long term conservation is a hot topic, give it a look!
- [Datasets](#datasets) - Entering the machine learning and artificial intelligence dimension. Maybe here you can find a dataset to train your new shiny model!


## Contributing

A community-driven list is, at its core, driven by contributions. If you stumble upon a great service or library, or find mistakes, please get involved by starting a discussion or suggesting a change via a pull request.

- [Suggest a new entry](https://github.com/OneOffTech/awesome-pdf/issues/new/choose)
- [Discuss about the categorisation](https://github.com/OneOffTech/awesome-pdf/issues/new/choose)
- [Correct mistakes](https://github.com/OneOffTech/awesome-pdf/pulls)

Please see [Contributing](./.github/CONTRIBUTING.md) for details.

---

## Parsers, OCR and extraction

- [Parxy](https://github.com/OneOffTech/parxy) - A PDF parsers gateway. Access different parsers using a unified API.
- [Docling](https://github.com/docling-project/docling) - Simplifies document processing, parsing diverse formats — including advanced PDF understanding — and providing seamless integrations with the gen AI ecosystem.
- [SmolDocling](https://huggingface.co/spaces/ds4sd/SmolDocling-256M-Demo) - A multimodal Image-Text-to-Text model designed for efficient document conversion. It retains Docling's most popular features while ensuring full compatibility with Docling through seamless support for DoclingDocuments.
- [Filimoa/open-parse](https://github.com/Filimoa/open-parse/) - Improved file parsing for LLM's.
- [VikParuchuri/surya](https://github.com/VikParuchuri/surya) - OCR, layout analysis, reading order, table recognition in 90+ languages
- [UniModal4Reasoning/StructEqTable-Deploy](https://github.com/UniModal4Reasoning/StructEqTable-Deploy) - A High-efficiency Open-source Toolkit for Table-to-Latex Task
- [huridocs/pdf-document-layout-analysis](https://github.com/huridocs/pdf-document-layout-analysis) - A Docker-based service for analyzing PDF document layouts, enabling segmentation and classification of elements like text, titles, images, and tables.
- [Reducto](https://reducto.ai/) Document Ingestion API
- [adithya-s-k/omniparse](https://github.com/adithya-s-k/omniparse) - OmniParse is a platform that ingests and parses any unstructured data into structured, actionable data optimized for GenAI (LLM) applications. Whether you are working with documents, tables, images, videos, audio files, or web pages, OmniParse prepares your data to be clean, structured, and ready for AI applications such as RAG, fine-tuning, and more
- [lumina-ai-inc/chunkr](https://github.com/lumina-ai-inc/chunkr) - Vision model based PDF chunking.
- [lumina-ai-inc/PaddleOCR](https://github.com/lumina-ai-inc/PaddleOCR) Multilingual OCR toolkits based on PaddlePaddle (practical ultra lightweight OCR system, support 80+ languages recognition, provide data annotation and synthesis tools, support training and deployment among server, mobile, embedded and IoT devices)
- [allenai/olmocr](https://github.com/allenai/olmocr) - Toolkit for linearizing PDFs for LLM datasets/training.
- [opendatalab/PDF-Extract-Kit](https://github.com/opendatalab/PDF-Extract-Kit) - A Comprehensive Toolkit for High-Quality PDF Content Extraction.
- [smalot/pdfparser](https://github.com/smalot/pdfparser) - A standalone PHP library, provides various tools to extract data from a PDF file.
- [Unstructured-IO/unstructured](https://github.com/Unstructured-IO/unstructured) - Open source libraries and APIs to build custom preprocessing pipelines for labeling, training, or production machine learning pipelines. Commercial service available on [Unstructured.io](https://unstructured.io/)
- [PyMuPDF, LLM & RAG](https://pymupdf.readthedocs.io/en/latest/rag.html)
- [PyMuPDF4LLM — PyMuPDF4LLM documentation](https://pymupdf4llm.readthedocs.io/en/latest/)
- [CatchTheTornado/pdf-extract-api: Document (PDF) extraction and parse API using state of the art modern OCRs + Ollama supported models. Anonymize documents. Remove PII. Convert any document or picture to structured JSON or Markdown](https://github.com/CatchTheTornado/pdf-extract-api)
- https://github.com/climatepolicyradar/navigator-document-parser Parsing PDFs and websites containing laws and policies - the pdf output is very similar to what the Adobe API returns #ml


## Creation and production

- [shipsaas/docking](https://github.com/shipsaas/docking) - Shared-microservice that takes over the document templates management & render/export PDF.
- [WeasyPrint](https://weasyprint.org/).
- [qpdf/qpdf](https://github.com/qpdf/qpdf) - A content-preserving PDF document transformer.
- [Stirling-Tools/Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF) - A locally hosted web-based PDF manipulation tool using Docker. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.
- [unjs/unpdf](https://github.com/unjs/unpdf) - Utilities to work with PDFs in Node.js, browser and workers.
- [PdfRest](https://pdfrest.com/) PDF Api to create, shrink and compress.
- [Gotenberg](https://gotenberg.dev/) - A Docker-powered stateless API for creating PDF files from templates in various formats, e.g., HTML, Markdown, Word, Excel.
- [Smallpdf](https://smallpdf.com/) - Set of tools to extract and manipulate PDF content.
- [typst/typst](https://github.com/typst/typst) - A new markup-based typesetting system that is powerful and easy to learn.
- [Vexlio](https://vexlio.com/) - Tool to create diagrams and export in SVG or PDF.

## Readers and viewers

- [mozilla/pdf.js](https://github.com/mozilla/pdf.js) - PDF Reader in JavaScript.
- [agentcooper/react-pdf-highlighter](https://github.com/agentcooper/react-pdf-highlighter) - Set of React components for PDF annotation.
- [Sioyek](https://sioyek.info/) is a PDF viewer with a focus on technical books and research papers (desktop app).


## Accessibility

- [veraPDF](https://openpreservation.org/tools/verapdf/) - Verify compliance with PDF/A and PDF/UA specification (via Open Preservation Foundation).


## Datasets

- [tpn/pdfs](https://github.com/tpn/pdfs) - Technically-oriented PDF Collection (Papers, Specs, Decks, Manuals, etc).
- [pdf-association/pdf-corpora](https://github.com/pdf-association/pdf-corpora) - An index of PDF-centric corpora.
- [HURIDOCS/pdf-document-layout-analysis · Hugging Face](https://huggingface.co/HURIDOCS/pdf-document-layout-analysis)
- [DS4SD/DocLayNet: DocLayNet](https://github.com/DS4SD/DocLayNet) - A Large Human-Annotated Dataset for Document-Layout Analysis.
- [gipplab/pdf-benchmark](https://github.com/gipplab/pdf-benchmark) - A Benchmark of PDF Information Extraction Tools using a Multi-Task and Multi-Domain Evaluation Framework for Academic Documents.
- [DocBank Dataset](https://github.com/doc-analysis/DocBank) - DocBank is a new large-scale dataset that is constructed using a weak supervision approach. It enables models to integrate both the textual and layout information for downstream tasks. The current DocBank dataset totally includes 500K document pages, where 400K for training, 50K for validation and 50K for testing.


---

## Licence

This list is licenced under [CC0 1.0 Universal](./licence).