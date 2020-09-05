```yaml
Events:
  Type    Reason                     Age                   From                     Message
  ----    ------                     ----                  ----                     -------
  Normal  ChaosEngineInitialized     6m30s                 chaos-operator           timeout1-runner created successfully
  Normal  ExperimentDependencyCheck  6m4s                  timeout1-runner          Experiment resources validated for Chaos Experiment 'pod-delete'
  Normal  ExperimentJobCreate        5m59s                 timeout1-runner          Experiment Job 'pod-delete-j3pndg' created for Chaos Experiment 'pod-delete'
  Normal  PreChaosCheck              3m4s                  pod-delete-j3pndg-tjwr5  AUT is Running successfully
  Normal  ChaosInject                2m44s (x3 over 3m4s)  pod-delete-j3pndg-tjwr5  Injecting pod-delete chaos on application pod
  Normal  PostChaosCheck             2m34s                 pod-delete-j3pndg-tjwr5  AUT is Running successfully
  Normal  Summary                    2m34s                 pod-delete-j3pndg-tjwr5  pod-delete experiment has been Passed
  Normal  ExperimentJobCleanUp       2m28s                 timeout1-runner          Experiment Job 'pod-delete-j3pndg' will be retained
  Normal  ChaosEngineCompleted       2m22s                 chaos-operator           Chaos Engine completed, will delete or retain the resources according to jobCleanUpPolicy
```⏎         
