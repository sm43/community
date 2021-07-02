# Tekton Enhancement Proposals (TEPs)

| TEP  | Title  | Status   | Last Updated  |
|------|--------|----------|---------------|
|[TEP-0001](0001-tekton-enhancement-proposal-process.md) |~~Tekton Enhancement Proposal Process~~| Done | 2020-06-11 |
|[TEP-0002](0002-custom-tasks.md) |~~Custom Tasks~~| Done | 2020-07-07 |
|[TEP-0003](0003-tekton-catalog-organization.md) |~~Tekton Catalog Organization~~| Done | 2021-02-09 |
|[TEP-0004](0004-task-results-in-final-tasks.md) |~~Task Results in Final Tasks~~ | Done | 2021-06-03 |
|[TEP-0005](0005-tekton-oci-bundles.md) | ~~Tekton OCI Bundles~~ | Done | 2020-08-13 |
|[TEP-0006](0006-tekton-metrics.md) | ~~Tekton Metrics~~ | Done | 2020-07-13 |
|[TEP-0007](0007-conditions-beta.md) | ~~Conditions Beta~~ | Done | 2021-06-03 |
|[TEP-0008](0008-support-knative-service-for-triggers-eventlistener-pod.md) | ~~Support Knative Service for Triggers EventListener Pod~~ | Done | 2020-08-25 |
|[TEP-0009](0009-trigger-crd.md) | ~~Trigger CRD~~ | Done | 2020-09-08 |
|[TEP-0010](0010-optional-workspaces.md) | ~~Optional Workspaces~~ | Done | 2020-10-15 |
|[TEP-0011](0011-redirecting-step-output-streams.md) | ~~redirecting-step-output-streams~~ | Done | 2020-11-02 |
|[TEP-0012](0012-api-spec.md) | ~~API Specification~~ | Done | 2020-08-10 |
|[TEP-0014](0014-step-timeout.md) | ~~Step Timeout~~ | Done | 2020-09-10 |
|[TEP-0015](0015-pending-pipeline.md) | ~~pending-pipeline-run~~ | Done | 2020-09-10 |
|[TEP-0016](0016-concise-trigger-bindings.md) | ~~Concise Embedded TriggerBindings~~ | Done | 2020-09-15 |
|[TEP-0019](0019-other-arch-support.md) | ~~Other Arch Support~~ | Done | 2020-09-30 |
|[TEP-0020](0020-s390x-support.md) | ~~s390x Support~~ | Done | 2021-06-04 |
|[TEP-0021](0021-results-api.md) | ~~Tekton Results API~~ | Done | 2020-10-26 |
|[TEP-0022](0022-trigger-immutable-input.md) | Triggers - Immutable Input Events | implementable | 2020-09-29 |
|[TEP-0024](0024-embedded-trigger-templates.md) | Embedded TriggerTemplates | implemented | 2020-10-01 |
|[TEP-0025](0025-hermekton.md) | Hermetic Builds | implementable | 2020-09-11 |
|[TEP-0026](0026-interceptor-plugins.md) | interceptor-plugins | implementable | 2020-10-08 |
|[TEP-0027](0027-https-connection-to-triggers-eventlistener.md) | HTTPS Connection to Triggers EventListener | implementable | 2020-11-01 |
|[TEP-0028](0028-task-execution-status-at-runtime.md) | task-exec-status-at-runtime | implemented | 2021-06-03 |
|[TEP-0029](0029-step-workspaces.md) | step-and-sidecar-workspaces | implementable | 2020-10-02 |
|[TEP-0030](0030-workspace-paths.md) | workspace-paths | proposed | 2020-10-18 |
|[TEP-0031](0031-tekton-bundles-cli.md) | tekton-bundles-cli | implemented | 2021-03-26 |
|[TEP-0032](0032-tekton-notifications.md) | Tekton Notifications | proposed | 2020-11-18 |
|[TEP-0033](0033-tekton-feature-gates.md) | Tekton Feature Gates | implementable | 2021-03-23 |
|[TEP-0035](0035-document-tekton-position-around-policy-authentication-authorization.md) | document-tekton-position-around-policy-authentication-authorization | implementable | 2020-12-09 |
|[TEP-0036](0036-start-measuring-tekton-pipelines-performance.md) | Start Measuring Tekton Pipelines Performance | proposed | 2020-11-20 |
|[TEP-0037](0037-remove-gcs-fetcher.md) | Remove `gcs-fetcher` image | implementing | 2021-01-27 |
|[TEP-0038](0038-generic-workspaces.md) | Generic Workspaces | proposed | 2020-12-11 |
|[TEP-0039](0039-add-variable-retries-and-retrycount.md) | Add Variable `retries` and `retry-count` | proposed | 2021-01-31 |
|[TEP-0040](0040-ignore-step-errors.md) | Ignore Step Errors | proposed | 2021-02-04 |
|[TEP-0041](0041-tekton-component-versioning.md) | Tekton Component Versioning | implementable | 2021-04-26 |
|[TEP-0042](0042-taskrun-breakpoint-on-failure.md) | taskrun-breakpoint-on-failure | proposed | 2021-03-21 |
|[TEP-0044](0044-decouple-task-composition-from-scheduling.md) | Decouple Task Composition from Scheduling | proposed | 2021-03-10 |
|[TEP-0045](0045-whenexpressions-in-finally-tasks.md) | WhenExpressions in Finally Tasks | implemented | 2021-06-03 |
|[TEP-0046](0046-finallytask-execution-post-timeout.md) | Finally tasks execution post pipelinerun timeout | implementable | 2021-04-14 |
|[TEP-0047](0047-pipeline-task-display-name.md) | Pipeline Task Display Name | proposed | 2021-02-10 |
|[TEP-0049](0049-aggregate-status-of-dag-tasks.md) | Aggregate Status of DAG Tasks | implemented | 2021-06-03 |
|[TEP-0050](0050-ignore-task-failures.md) | Ignore Task Failures | proposed | 2021-02-19 |
|[TEP-0051](0051-ppc64le-architecture-support.md) | ppc64le Support | proposed | 2021-01-28 |
|[TEP-0052](0052-tekton-results-automated-run-resource-cleanup.md) | Tekton Results: Automated Run Resource Cleanup | implementable | 2021-03-22 |
|[TEP-0053](0053-nested-triggers.md) | Nested Triggers | implementable | 2021-04-15 |
|[TEP-0056](0056-pipelines-in-pipelines.md) | Pipelines in Pipelines | proposed | 2021-03-08 |
|[TEP-0057](0057-windows-support.md) | Windows support | proposed | 2021-03-18 |
|[TEP-0058](0058-graceful-pipeline-run-termination.md) | Graceful Pipeline Run Termination | implementable | 2021-04-27 |
|[TEP-0059](0059-skipping-strategies.md) | Skipping Strategies | implementable | 2021-05-06 |
|[TEP-0060](0060-remote-resource-resolution.md) | Remote Resource Resolution | proposed | 2021-05-17 |
|[TEP-0061](0061-allow-custom-task-to-be-embedded-in-pipeline.md) | Allow custom task to be embedded in pipeline | implemented | 2021-05-26 |
|[TEP-0062](0062-catalog-tags-and-hub-categories-management.md) | Catalog Tags and Hub Categories Management | implementable | 2021-03-30 |
|[TEP-0063](0063-workspace-dependencies.md) | Workspace Dependencies | proposed | 2021-04-23 |
|[TEP-0066](0066-dogfooding-tekton.md) | Dogfooding Tekton | proposed | 2021-05-16 |
|[TEP-0067](0067-tekton-catalog-pipeline-organization.md) | Tekton Catalog Pipeline Organization | implementable | 2021-02-22 |
|[TEP-0070](0070-tekton-catalog-task-platform-support.md) | Platform support in Tekton catalog | proposed | 2021-06-02 |
