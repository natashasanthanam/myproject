# myproject

A [workflowr][] project.

[workflowr]: https://github.com/jdblischak/workflowr
curl -G \
   -HAccept:text/csv \
   "http://127.0.0.1:5000/ukbrest/api/v1.0/phenotype" \
   --data-urlencode "columns=c20414_0_0 as frequency” \
   --data-urlencode "columns=c20403_0_0 as amount ” \
   --data-urlencode "columns=c20416_0_0 as six ” \
  --data-urlencode "columns=c20413_0_0 as  inabilitytocease” \
  --data-urlencode "columns=c20407_0_0 as frequency failure” \
 --data-urlencode "columns=c20412_0_0 as frequencymorningdrink” \
 --data-urlencode "columns=c20409_0_0 as frequencyguilty” \
 --data-urlencode "columns=c20408_0_0 as frequencymemoryloss” \
 --data-urlencode "columns=c20411_0_0 as injured” \
 --data-urlencode "columns=c20405_0_0 as someoneconcerned” \
--data-urlencode "columns=c20410_0_0 as agewhenlastcommented” \
> alcohol.csv
