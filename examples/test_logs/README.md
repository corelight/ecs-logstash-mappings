Test the pipeline without outputting to your cluster.
1) copy the test log to path to read  
`cp corelight_test.log /tmp/corelight_test.log`
2) enable output, either use output to a file or stdout  
  a) file out  
    copy `9999-corelight-ecs-test-file-output.conf.disabled` to your pipelines directory and remove the appended `.disabled`
  b) stdout  
    copy `9999-corelight-ecs-test-stdout-output.conf.disabled` to your pipelines directory and remove the appended `.disabled`