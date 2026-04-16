# Innovation memo: GluonTS Probabilistic Planning

        ## Research anchor

        - Paper: GluonTS: Probabilistic and Neural Time Series Modeling in Python
        - Score: 9.68/10
        - Official repo: https://github.com/awslabs/gluonts

        ## What this project does differently

        - Turn upstream probabilistic forecasting capabilities into a production-style application with operations-facing workflows.
- Add deployment packaging, monitoring hooks, and screenshot-ready demos instead of notebook-only output.
- Connect model behavior to concrete business decisions so the project is easier to evaluate and present.

        ## What the upstream code showed

        - No container packaging signal detected, which makes demos and deployment less portable.
- Mixed filename conventions detected: PascalCase, kebab-case, snake_case.
- Open maintenance markers detected: FIXME in 9 file(s), TODO in 87 file(s), XXX in 1 file(s).
- Large files that may benefit from decomposition: test/mx/model/gp_forecaster/data.py (5495 lines), test/mx/distribution/test_mx_distribution_inference.py (1361 lines), src/gluonts/nursery/tsbench/src/tsbench/config/dataset/datasets.py (1244 lines).

        ## Why the difference matters

        - It makes the original idea easier to explain to operators, hiring managers, and stakeholders.
        - It moves the work from a research or notebook framing into a product and deployment framing.
        - It produces stronger portfolio evidence because the system includes UI, docs, API behavior, screenshots, and clear business outcomes.

        ## Easier production path

        - Keep the first version lightweight and easy to run locally.
        - Preserve a visible API surface, health endpoint, and operator workflow.
        - Package evaluation, screenshots, and runbooks alongside the model or LLM logic.
