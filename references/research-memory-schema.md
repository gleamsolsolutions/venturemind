# Research Memory Schema

Use only an authorized persistent store. If none exists, save a local project artifact only when the user asks or the environment's normal workspace policy permits.

Suggested JSON record:
```json
{
  "research_id": "stable-id",
  "topic": "topic",
  "decision_question": "decision",
  "created_at": "ISO-8601",
  "last_verified_at": "ISO-8601",
  "geography": ["target market"],
  "customer_segments": ["segment"],
  "competitors": [{"name": "name", "url": "https://..."}],
  "problem_clusters": [{"problem": "problem", "evidence_urls": []}],
  "keyword_clusters": [{"keyword": "keyword", "intent": "commercial", "source": "tool"}],
  "domain_candidates": [{"domain": "example.com", "status": "unverified"}],
  "verdict": "needs-validation",
  "confidence": "medium",
  "key_assumptions": [],
  "unresolved_questions": [],
  "source_urls": [],
  "refresh_required": true
}
```

Never store passwords, access tokens, private customer data, sensitive personal information or private community content. Research memory is a lead for future work, not proof. Re-open sources and refresh time-sensitive facts before relying on them.
