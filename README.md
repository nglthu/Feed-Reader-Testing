# unit-test
+ write test using Jasmin's testing syntax
+ feed reader testing
e.g
	it('name are defined and not empty', function(){
			for(var i=0; i<allFeeds.length; i++){
				expect(allFeeds[i].name).toBeDefined();
				expect(allFeeds[i].name).not.toBeNull();
			}
		});
   
