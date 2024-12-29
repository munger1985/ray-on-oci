# usages of ray on oci

## ray submit multi-gpu jobs

### start ray cluster

```
ray start --head --dashboard-host 0.0.0.0 
```

### submit job

```
export RAY_ADDRESS="http://10.0.0.15:8265"

ray job submit --working-dir ./ -- python script.py
```

### video

https://www.bilibili.com/video/BV1WB6aYBEQ5/?vd_source=c3af40a59ceffa46f1ce5e424fb77c8d


## ray serve multi-gpu applcations as REST API


