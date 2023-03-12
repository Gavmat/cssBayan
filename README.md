# cssBayan

git commit -m "`date`" # Wed Aug 28 10:22:06 CST 2019
git commit -m "`date +'%Y-%m-%d'`" # 2019-08-28
git commit -m "Updated: `date +'%Y-%m-%d %H:%M:%S'`" # Updated: 2019-08-28 10:22:06
current="`date +'%Y-%m-%d %H:%M:%S'`"
msg="Updated: $current"
git commit -m "$msg" # Updated: 2019-08-28 10:22:06 

git commit -m "docs: add link to deploy (date +'%a, %b %e, %Y %H:%M:%S')"