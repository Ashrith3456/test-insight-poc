# TestInsight POC

End-to-end proof of concept for automated verification-test data processing. It combines numerical measurements, text logs, and image-based results into threshold decisions, statistical summaries, interactive visualizations, structured result tables, and a predefined report.

This portfolio/research POC contains no Ericsson-confidential information and is not an Ericsson product.

## Included

- CSV/JSON ingestion with schema validation
- Configurable PASS/FAIL rules by network technology
- Explainable robust anomaly detection
- Log extraction and root-cause categorization
- Image status and embedded-metadata extraction
- Interactive throughput, latency, pass/fail, and anomaly charts
- Automated HTML report and CSV/JSON result tables
- Accuracy, runtime, throughput, and usability-readiness evaluation
- Browser upload UI, JSON API, health endpoint, and batch CLI
- Unit and end-to-end tests
- Docker configuration and deployment recommendations

## Data provenance

Measurements use the Kaggle Cellular Network Analysis Dataset by Suraj520 under CC0/Public Domain. Companion logs, images, test IDs, and ground truth are synthetic and reproducible. They are not Ericsson verification data.

Dataset: https://www.kaggle.com/datasets/suraj520/cellular-network-analysis-dataset

## Quick start

1. Install Python 3.11 or newer.
2. Run: python -m pip install -r requirements.txt
3. Run: python -m testinsight process --input data/demo --output runtime/latest
4. Run: python -m testinsight serve
5. Open http://127.0.0.1:8000

## JD coverage

- Numerical, textual, and image-format analysis
- Modular automated application with browser UI, API, and CLI
- Interactive graphs, trends, statistics, and anomaly detection
- Log parsing, image extraction, and documented OCR strategy
- Automatic predefined report and table population
- Accuracy, efficiency, and usability-readiness evaluation
- Ericsson pilot checklist for authorized verification data
- Findings and future deployment recommendations

## Limitations

Demonstration thresholds require domain validation. Perfect mock-format accuracy does not establish real-world generalization. Real Ericsson validation requires authorized anonymized samples. Production deployment requires authentication, malware scanning, encryption, retention controls, and auditing.

The full source package is included as test-insight-poc-complete.zip.
