# Audit Certification Module

## Purpose
Verify that an Origami-generated output conforms to its declared constraint set.

## How It Works
- Compares final synthesis to initial constraint logic
- Checks F/I/P tag presence and flow integrity
- Returns audit result: pass / warning / fail

## YAML Scaffold Example
constraint: "No diagnosis without lab confirmation"
synthesis: "Suggests treatment before labs"
audit_cert_result: "fail"
