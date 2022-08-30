gcloud builds submit --tag gcr.io/propane-primacy-346205/dash-gsearch-serp --project=propane-primacy-346205

gcloud run deploy --image gcr.io/propane-primacy-346205/dash-gsearch-serp --platform managed 
--project=propane-primacy-346205 --allow-unauthenticated