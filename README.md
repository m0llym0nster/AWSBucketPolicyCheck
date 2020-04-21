# AWSBucketPolicyCheck
!!!still draft/testing this out, be careful!

pulls all buckets in s3 and all principals from bucket policies

have instance role or aws credentials setup with access to s3 list all buckets and get bucket policy

./checkForRoot
puts output called BucketPol.csv in directory it is ran from

![csv ouptut example](https://github.com/m0llym0nster/AWSBucketPolicyCheck/blob/master/images/Output.png)

soonest - will check with more sids than 1
sooner - will look for root in principals listing
soon - will look for dangerous allow permissions (* and Put* specifically)
eventually - will add list of things to look for for choices and place for output to go
