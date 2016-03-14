nessus CHANGELOG
================

0.1.2
-----
- [Alexander Kaasjager] Set RPM package action from default (:install) to prevent recipe from breaking chef-client when older package is found.
	(see https://docs.chef.io/resource_rpm_package.html). There is no such option for dpkg, so that is set to :install.

0.1.1
-----
- [Jason Rohwedder] - Add users through nessus::users


0.1.0
-----
- [Jason Rohwedder] - Initial release of nessus
