# PPT Design Workflow

A Codex skill for creating professional presentations through a structured three-stage workflow: content planning, visual direction exploration, and high-fidelity editable PPTX production.

## Features

- Converts source files or requirements into a structured presentation outline
- Produces detailed page-by-page content plans
- Generates three distinct visual directions as full-deck mosaics
- Preserves confirmed content, slide count, and slide order
- Creates high-fidelity, editable PowerPoint presentations
- Keeps titles, body text, numbers, labels, and simple charts editable
- Preserves complex visual effects as high-resolution image assets
- Renders slide previews for visual comparison and quality assurance
- Checks content accuracy, typography, layout, consistency, and editability

## Workflow

### Stage 1: Content Planning

The skill analyzes the provided materials and produces:

- Presentation objective and narrative
- Section structure
- Slide-by-slide outline
- Key messages and supporting evidence
- Recommended visual format for each slide
- Missing information and confirmation items

The visual design stage begins only after the content has been approved.

### Stage 2: Visual Direction Exploration

Based on the approved content, the skill generates three complete visual directions:

- Option A
- Option B
- Option C

Each option is presented as a full-deck mosaic containing every slide in the correct order and 16:9 format.

The three options differ in layout, typography, information density, chart language, image usage, background treatment, and visual hierarchy—not just color.

No PPTX file is generated during this stage.

### Stage 3: Editable PPTX Production

After a visual direction is selected, the skill creates an editable PowerPoint presentation using a hybrid reconstruction strategy:

- Important text is rebuilt with native PowerPoint text boxes
- Simple shapes, tables, and charts remain editable
- Complex illustrations, textures, photographs, and visual effects are preserved as high-resolution assets
- Low-resolution mosaic thumbnails are not used as full-slide backgrounds
- All slides are rendered and checked against the approved content and visual direction

## Output

The final delivery may include:

- Editable `.pptx` file
- Rendered slide previews or preview PDF
- Implementation notes covering:
  - Editable text, shapes, and charts
  - Embedded visual assets
  - Text retained inside complex images
  - Approximate chart data
  - Font substitutions

## Installation

Clone or download this repository and place the folder in your Codex skills directory:

### Windows

```text
%USERPROFILE%\.codex\skills\ppt-design-workflow
