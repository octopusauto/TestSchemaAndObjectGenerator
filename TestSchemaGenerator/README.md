Test Schema and Object generator project .it is a JAXB based project to generate objects and read test daat xmls.

While using this project the end user has to provide Test data xmls which will be used in the project as Input.
Using those xmls, corresponding test schema and objects will be generated.

Sample Test Data xml provided by manual tester:
<?xml version="1.0"?>
<data>
	<test name="test1">
		<username>username1</username>
		<password>password1</password>
	</test>
	<test name="test2">
		<username>username2</username>
		<password>password2</password>
	</test>
	<test name="test3">
		<username>username3</username>
		<password>password3</password>
		<emplastname>john</emplastname>
	</test>
	<test name="test3">
		<username>username3.1</username>
		<password>password3.1</password>
		<empid>00777</empid>
		<empSpouseName>JohnCena</empSpouseName>
		<empHeight>5</empHeight>
	</test>

	<test name="test4">
		<username>username4.1</username>
		<password>password4.1</password>
	</test>	
</data>

The Schema will be used to generate Objects and Jar will be created in the end.

That jar will be used as dependency in the framework project to read the data from the xmls .

