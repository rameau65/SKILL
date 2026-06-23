# PIPELINE_ROUTER

## Purpose
Select the correct pipeline before selecting tools or engines.

## Router Principle
Do not start by writing prompts. Start by classifying the production request.

## Pipeline Types

| User Intent | Pipeline |
|---|---|
| Make something like this video | REFERENCE_VIDEO_PIPELINE |
| Create meditation video | MEDITATION_CINEMA_PIPELINE |
| Create Hanmaum educational/documentary content | HANMAUM_DOCUMENTARY_PIPELINE |
| Create YouTube Short | SHORTS_CINEMA_PIPELINE |
| Create documentary montage | DOCUMENTARY_MONTAGE_PIPELINE |
| Create AI art poetic film | AI_POETRY_FILM_PIPELINE |
| Create explainer | EDUCATIONAL_EXPLAINER_PIPELINE |
| Create brand teaser | BRAND_FILM_PIPELINE |
| Convert long content to clips | CLIP_FACTORY_PIPELINE |
| Create report/PPT/doc | INFOGRAPHIC_DOCUMENT_PIPELINE |

## Router Questions
1. Is there a reference video or existing source?
2. Is the target output video, document, image, music, or channel package?
3. Is the style cinematic, educational, meditative, documentary, or short-form?
4. Does the work require research?
5. Is approval needed before production?
6. Which engines are mandatory?
7. What quality gates must be passed?

## Router Output

```text
Selected Pipeline:
Required Agents:
Required Engines:
Reference Inputs:
Research Needed:
Approval Points:
Delivery Format:
```

## Rule
If a request is ambiguous, choose the safest production pipeline and state the assumption.
