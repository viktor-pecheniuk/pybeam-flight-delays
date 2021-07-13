# python beam pipeline

## Command to trigger DataFlow job with 60 seconds sliding window size and 30 seconds shift
python3 -m average_delay_pipeline --runner=dataflow --project=webinar-315516 --region=us-central1 --streaming --temp_location=gs://python-dataflow-staff/temp/ --staging_location=gs://python-dataflow-staff/staging --averagingInterval=15.0 --pipeline_project=webinar-315516 --speedupFactor=15.0