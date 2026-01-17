# Analysis: GDPR: People are not assets! - Episode 16, Tetradian on Architectures

## Executive Summary
The video emphasizes that under impending GDPR regulations, people—whether customers or employees—are not assets owned by companies; instead, the **relationship** with the person is the true asset that must be managed carefully. It warns that GDPR's requirements for explicit opt-in and single-use personal data will disrupt business models like spam and cold-calling, urging architects to distinguish relationship information from the relationship itself to avoid CRM pitfalls.

## Key Takeaways
- **GDPR's global impact**: The EU's General Data Protection Regulation (GDPR) requires explicit opt-in and single agreed use of personal info, threatening non-compliant models like spam and cold-calling.
- **People ≠ assets**: Companies do not own people; treating them as assets equates to slavery—only the **relationship** is the asset, which exists between parties and can be ended unilaterally.
- **Manage relationships as assets**: Apply standard CRUD operations (create, read, update, delete, maintain) to relationships, just like any data or physical asset.
- **Information ≠ relationship**: Data about a relationship (e.g., in CRM systems) is not the relationship itself—confusing them leads to architectural errors.
- **Real-world example**: Misusing purchase data for repeated ads (e.g., Amazon shirt sellers) destroys relationships by violating single-use principles.

## Actionable Insights / Tutorials
- **Treat relationships as droppable assets**: Design systems recognizing that either party can end the relationship at any time—monitor for silent terminations (e.g., customer ignores ads post-purchase).
- **Avoid CRM misconceptions**: In enterprise architecture, separate **relationship metadata** from the actual relationship; do not assume CRM data equals the real customer bond.
- **GDPR compliance in architecture**: Implement explicit opt-in, enforce single-use data policies, and manage personal info with CRUD functions to maintain relationship assets without ownership claims.
- **Audit business models**: Review models reliant on unsolicited contact (spam, cold-calling) and pivot to relationship-centric designs before GDPR enforcement.

## Quotes
- "People are not assets they're not possessed by a company neither as customers nor as employees the crucial understanding here is that the relationship with the person is the asset not the person themselves."
- "In fact the only time when a person is an aspect [asset] is when they're a slave which is not exactly a good way to describe anything."
- "Information about a relationship is not the same as the relationship itself if we make that mistake then that's where a lot of problems come with CRM systems."
- "Don't make that mistake in your architecture so the crucial one here is to understand that people are not assets it is the relationship that we have with those people that is the actual asset."