# release-micro
Release server for RCM micro-services

# micro, cloud 만 제거
`
find ./ -name "*0.0.3-20220819*"  -type f -ls -exec rm {} +
find ./ -name "*0.0.3-20220822.03*"  -type f -ls -exec rm {} +
find ./ -name "*0.0.3-20220822.04*"  -type f -ls -exec rm {} +
find ./ -name "micro*20220804*"  -type f -ls -exec rm {} +
find ./ -name "micro*20220805*"  -type f -ls -exec rm {} +
find ./ -name "micro*20220808*"  -type f -ls -exec rm {} +
find ./ -name "micro*20220809*"  -type f -ls -exec rm {} +
find ./ -name "micro*20220730*"  -type f -ls -exec rm {} +
find ./ -name "micro*20220731*"  -type f -ls -exec rm {} +
find ./ -name "micro*20220801*"  -type f -ls -exec rm {} +
find ./ -name "micro*20220802*"  -type f -ls -exec rm {} +
find ./ -name "cloud*20220730*"  -type f -ls -exec rm {} +
find ./ -name "cloud*20220731*"  -type f -ls -exec rm {} +
find ./ -name "cloud*20220801*"  -type f -ls -exec rm {} +
find ./ -name "cloud*20220802*"  -type f -ls -exec rm {} +
`

# 전체 제거 
`
find ./ -name "*20220801*"  -type f -ls -exec rm {} +
`