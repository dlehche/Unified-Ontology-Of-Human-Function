# Connecting Human Models Through Human Function: Toward a Common Computational Protocol for Whole-Person Modeling

## Conceptual architecture and research agenda

> **Version-controlled GitHub text edition of the Zenodo Version 1.0 preprint.**  
> Canonical archival record and PDF: https://doi.org/10.5281/zenodo.23180973  
> [中文全文](Human_Model_Interoperability_ZH_V1.0.md) · [Publication overview](README.md)

**Lei Che**

MoveTips Technology (Beijing) Co., Ltd.

Beijing, China

Correspondence: dlehche@gmail.com

Version 1.0 \| 6 October 2026

DOI: 10.5281/zenodo.23180973

License: Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)

Copyright © 2026 Lei Che and MoveTips Technology (Beijing) Co., Ltd.

Keywords: Human function; Whole-person modeling; Model interoperability; UOHF; Human Function World Model; Functional capacity; Functional engagement

# Abstract

Heterogeneous human models can concern the same person while describing different constructs, times and possible outcomes. We propose human function as a common relational coordinate for their joint interpretation. The architecture connects task demands, evidence-supported capacity, actual functional engagement, performance, cost, boundaries and recovery while preserving native medical, physiological, psychological, cognitive, movement, nutritional, behavioral, environmental and device-model outputs. The Unified Ontology of Human Function supplies semantic identities and governed relations; the Human Function World Model coordinates a typed network with recursive submodels, distinct graph views and versioned updates. General interoperability principles are separated from HFWM conventions and domain-specific measurement rules. We position the proposal against functional classification, higher-level ontology fusion, context-based knowledge fusion and model-composition standards. A hypothetical stair-descent case traces how independent capacity support and qualified process observations yield a specific functional judgment, how missing inputs limit only dependent conclusions, and how assistance or medical forecasts remain distinct. The evaluation agenda compares matched-evidence alternatives across semantic, measurement, computational, predictive and practical outcomes. This is a conceptual architecture with explicit testable consequences, not evidence of universal model compatibility or clinical benefit.

# 1. The scientific problem: making different models jointly intelligible

A disease forecast, a physiological simulation, a movement analysis and an account of everyday demands may describe the same individual while answering different questions. Their outputs cannot be treated as interchangeable merely because they appear in one record. What is needed is a way to relate those answers to what this person must sustain or accomplish, which bodily capacities are available, how those capacities are actually used, and what changes after action or new evidence. This is a problem of computational interpretation as well as data exchange.

Integrated modeling is not new. Medical digital-twin research already addresses individualized simulation and integration. Higher-level fusion has long used ontologies to represent situations and relationships, and context-based knowledge fusion has explicitly considered the autonomy of contributing sources. The question is not whether these fields have discovered integration, but which person-level relations should be made explicit when their outputs concern human function.\[1,2,3\]

We propose an architecture in which human function organizes heterogeneous model contributions around the same continuing person. Its central relationship connects task demands, evidence-supported capacity, actual functional engagement, performance, cost, boundaries and recovery. The intended contribution is a specified organization of these relationships and their computational responsibilities, together with a traceable cross-model example and a falsifiable evaluation agenda. It is not a claim that a new label alone improves inference.

This work develops the author’s published UOHF and HFWM research program and specifies a cross-model interoperability architecture centered on human function. The paper distinguishes semantic commitments, architecture design requirements, external standards, and items that still require empirical calibration. The common protocol is proposed rather than internationally adopted; the cases are hypothetical design analyses, not reported patient outcomes.\[4,5,6\]

# 2. Human function, UOHF and HFWM are different layers

Human function is defined in this framework as “the body’s capacity to be appropriately engaged to meet internal and external demands.” Capacity is not the actual process of using it. Appropriate use is conditional on the person, demand, context and relevant boundaries, rather than a single movement appearance, population mean or productivity target. Human function is an organizing coordinate, not a synonym for health or the entirety of a person.\[4,5\]

The Unified Ontology of Human Function (UOHF) provides semantic identities, object distinctions and governed relations. The Human Function World Model (HFWM) uses that semantic foundation to organize states, evidence, actions, feedback and longitudinal updating for the same person. Domain models supply their own mechanisms, estimators, observations, predictions or qualified judgments. An organ model is therefore not a capacity object, and a model output is not automatically a personal fact.\[6,7\]

Table 1 separates the general proposal from the HFWM realization and the domain rules needed to make it operational. This separation is essential for a public interoperability claim: shared meaning does not require every participant to use one vendor, one algorithm or one internal variable name.

**Table 1. Three levels of the interoperability proposal.**

| **Level**                   | **What is specified**                                                                                               | **What remains open or distinct**                                                                                  |
|-----------------------------|---------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| General organizing proposal | Bind model contributions to the same person, demand, conditions, time and justified interpretation.                 | Other ontologies and implementations can be aligned through explicit, tested mappings.                             |
| HFWM realization            | UOHF references; one coordinating kernel; typed model network; four graph views; capacity and engagement contracts. | The 18/104 catalogue and three-valued labels are version-specific conventions, not internationally mandated codes. |
| Domain realization          | Measurement protocols, models, parameterization, construct interpretation, uncertainty and approved uses.           | Clinical, movement, cognitive and other methods retain their own evidence and professional boundaries.             |

This distinction organizes the source design for this paper; it does not add an ontology layer or a new physiological law.

The current capacity catalogue comprises 18 core capacities and 104 specific objects, including subcapacities and capacity components. It is a versioned semantic hierarchy, not a 104-dimensional interchangeable score vector or 104 validated measurement instruments. One model may support several capacities, and one capacity may depend on several models and observations. C07, Sustained Task Endurance Capacity, intentionally has no subordinate capacity objects in this version.\[8\]

Internal regulation, defense, recovery, consciousness, sleep–wake regulation, cognition and communication belong within the scope alongside movement. Medicine is one contributor, including diagnostic and predictive models, not the organizing center. Psychological experience, nutrition, environment, personal priorities and medical findings can remain in their native meanings even when no capacity interpretation is justified. A person’s choice not to undertake an activity must not be reclassified as a bodily deficit.\[7\]

# 3. The relationship to existing approaches

The World Health Organization’s ICF already distinguishes capacity in a standardized setting from performance in the current environment and incorporates environmental influences. HFWM should not claim to have invented the separation of ability and real-life accomplishment. Its actual-engagement construct concerns the bodily process through which available capacity is organized in a particular episode; that is not automatically equivalent to the ICF performance qualifier. A correspondence requires a defined construct and scope, not a name substitution.\[5,9\]

Little and Rogova provide a relational ontology approach to higher-level contextual understanding; Smirnov and colleagues analyze context-based fusion with attention to source structure and autonomy. These are direct intellectual comparators. The proposed HFWM contribution is the demand–capacity–engagement interpretation contract for human-model composition, not the general idea of preserving sources.\[2,3\]

CellML, SBML comp and FMI provide complementary facilities for model definition, composition and execution. They can support native coupling within an HFWM realization. PROV-O and UCUM can support provenance and unit representation. None should be portrayed as a weak alternative simply because its intended role differs from a functional interpretation contract.\[10,11,12,13,14\]

Table 2 identifies what should be compared. Its final column states questions for evaluation, not results establishing HFWM superiority. An alternative implementation that preserves the same relevant distinctions may perform equally well.

**Table 2. Closest approaches and the proposed comparison.**

| **Approach**                        | **Contribution to retain**                                             | **Question for a matched comparison**                                                                                               |
|-------------------------------------|------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| ICF-based functional representation | Capacity, performance, activities, participation and environment.      | Does explicit, separately evidenced actual engagement add information beyond a well-implemented ICF-informed representation?        |
| Higher-level ontology fusion        | Typed entities, processes and relations for contextual interpretation. | Does the specific functional relation improve target qualification, rather than merely adding labels?                               |
| Context-based knowledge fusion      | Contextual integration with source structure and autonomy considered.  | Can both systems preserve source dependence and distinguish changed demand from changed capacity?                                   |
| Model composition / co-simulation   | Native equations, components, connections and execution interfaces.    | Does the added person-level interpretation preserve valid coupled results while limiting unsupported task transfer?                 |
| Provenance-aware integration        | Recorded origin, derivation, responsibility and time.                  | Does interpretation distinguish a forecast, an observation and a justified judgment when provenance is otherwise equally available? |

Comparison dimensions are this manuscript’s analysis of the cited approaches. They do not assert that those approaches are incapable of extension.

# 4. One kernel, a typed model network and recursive composition

The HFWM architecture is organized as 1 + N with recursive submodels. The “1” is a versioned coordinating kernel, not a universal numerical formula; “N” denotes models with different computational roles. A model may contain submodels, but each execution must expand to a finite required subgraph. Adding a model does not automatically create an ontology child or require recalculating every capacity.\[7\]

The kernel coordinates identity, model and rule selection, evidence qualification, calculation plans, capacity and engagement judgments, safety, authority, versioning and report projections. Several software components can implement those responsibilities. Physiological models, statistical estimators, machine-learning predictors and rule systems retain their own mathematics. Their roles and permitted outputs, not their model-family names, determine how they enter a calculation.
