---
name: BookEditingAssistant
description: Advanced book editing and formatting assistant for publication-ready manuscripts
version: "1.0"
author: PublicationEditorAI
license: MIT
---
skills:
  - name: ChapterStructureAnalyzer
    description: Analyzes and enforces proper chapter structure with required elements
    capabilities:
      - quote_analysis: Identifies and validates opening quotes
      - medical_terms_identification: Recognizes and extracts medical terminology
      - did_you_know_detection: Locates and formats interesting facts sections
      - case_study_organization: Structures and highlights case studies
      - structural_compliance: Ensures all chapters follow required template

  - name: FormatConsistencyEnforcer
    description: Maintains consistent formatting throughout the manuscript
    capabilities:
      - font_standardization: Applies Times New Roman 12pt consistently
      - spacing_management: Enforces double-spacing throughout
      - margin_optimization: Sets 1-inch margins on all sides
      - paragraph_formatting: Implements 0.5-inch first-line indentation
      - header_footer_maintenance: Manages chapter headers and page numbers

  - name: ContentOptimizationEngine
    description: Optimizes content quality and eliminates redundancy
    capabilities:
      - repetition_eliminator: Identifies and removes duplicate content
      - ai_content_detector: Monitors and limits AI-generated content to <5%
      - plagiarism_scanner: Detects and flags plagiarized content
      - flow_optimizer: Enhances logical progression between sections
      - clarity_enhancer: Improves sentence structure and readability

  - name: EvidenceHighlighter
    description: Properly formats and highlights evidence-based content
    capabilities:
      - data_identification: Locates statistical data for bold formatting
      - research_finding_marker: Italicizes research findings
      - report_box_creator: Generates call-out boxes for reports
      - evidence_callout_generator: Creates highlighted evidence sections
      - reference_numbering: Maintains proper data reference numbering

  - name: VisualElementPreserver
    description: Maintains integrity of all images and visual components
    capabilities:
      - image_integrity_checker: Preserves all original images
      - placement_verifier: Maintains proper image positioning
      - caption_preservation: Keeps figure captions intact
      - resolution_maintainer: Ensures high-quality image retention
      - format_stability: Maintains original image file formats

  - name: BookAssemblyManager
    description: Compiles and assembles final publication-ready document
    capabilities:
      - chapter_sequencing: Orders chapters correctly
      - pagination_continuity: Ensures continuous page numbering
      - table_of_contents_generator: Creates auto-generated TOC
      - index_creator: Builds comprehensive subject index
      - final_qa_verification: Performs complete quality assurance

  - name: PublicationStandardsCompliance
    description: Ensures compliance with publishing industry standards
    capabilities:
      - pdf_compliance: Generates PDF/A compliant documents
      - print_readiness: Optimizes for 300 DPI printing
      - color_mode_management: Applies CMYK color standards
      - bleed_settings: Implements proper bleed margins
      - font_embedding: Ensures all fonts are embedded

configuration:
  formatting_standards:
    font_family: "Times New Roman"
    font_size: 12
    line_spacing: "double"
    margins: 
      top: 1
      bottom: 1
      left: 1
      right: 1
    units: "inches"
  
  content_limits:
    ai_content_threshold: 0.05
    plagiarism_threshold: 0.05
  
  chapter_template:
    opening_quote: true
    medical_terms_section: true
    did_you_know_box: true
    case_study_required: true
  
  quality_assurance:
    spell_check: true
    grammar_review: true
    style_guide_compliance: true
    accessibility_standards: true

integrations:
  - github_actions: true
  - markdown_support: true
  - pdf_processing: true
  - image_handling: true
  - text_analysis: true

dependencies:
  - python_version: ">=3.8"
  - libraries:
      - PyPDF2: ">=3.0.0"
      - python-docx: ">=0.8.11"
      - pillow: ">=9.0.0"
      - textstat: ">=0.7.3"
      - language_tool_python: ">=2.7.1"

usage:
  installation: "pip install book-editing-assistant"
  basic_command: "bookedit process-manuscript input.docx output.pdf"
  advanced_options:
    - "--preserve-images": "Maintains all visual elements"
    - "--highlight-evidence": "Emphasizes data and research findings"
    - "--check-plagiarism": "Scans for content originality"
    - "--optimize-flow": "Enhances chapter transitions"
    - "--publication-ready": "Applies final formatting standards"

documentation:
  repository: "https://github.com/PublicationEditorAI/book-editing-assistant"
  issues: "https://github.com/PublicationEditorAI/book-editing-assistant/issues"
  wiki: "https://github.com/PublicationEditorAI/book-editing-assistant/wiki"
