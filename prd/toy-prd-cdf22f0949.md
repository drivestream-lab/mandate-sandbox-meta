# Toy PRD: a greeting

The toy service greets a caller by name.

## Requirement

The service offers one function that returns "Hello, <name>" for a non-empty name.

## Wave evidence

The wave that builds this is released only with run-signed evidence for exactly the protected
tests named here. The caller workflow, the test set and the test-set digest are fixed by this
document when it is signed, never read from the commit under test.

```wave-evidence
repository: drivestream-lab/mandate-sandbox-svc
caller_workflow: .github/workflows/walking-skeleton-cdf22f0949.yml
test_set: [tests/unit]
expected_test_set_digest: e0a092de6309d9223804f36ba5f2c3b3b7c5fcfadbe516d86363dd9c769200a1
quarantine: []
plugins: []
```

Run: cdf22f0949
