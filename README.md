# FreeEMS History

This repository is to hold the details of each vehicle or engine to run on
FreeEMS as a historical record. This is useful just as a simple record, and also
to generate statistics and graphs from.

### Adding Yours

Once you've shown the community your achievements on the forum with some
supporting evidence such as video footage and hardware build details, you can
add your information to this database. If you don't want to, or don't know how
to use git, then you can simply download the yaml file, edit it, and upload to
the forum for someone else to integrate for you.

If you do add your own data, and have the necessary ruby prerequisits installed,
then before submitting it, please verify the file in one or both of these ways:

 - ruby -ryaml -e "p YAML.load_file(ARGV[0])" vehicles.yaml
 - ruby -ryaml -rpp -e "pp YAML.load_file(ARGV[0])" vehicles.yaml

The first one will print a large and dense block of data, or an error. The
second one will print a well formatted "pretty" block of data or an error.

### Thanks

Lastly, I offer my sincere heartfelt thanks to all of those who have become
involved with the project and especially those who have made the effort to run
the system on their cars. Thank you very much!

Fred.

