# Statement Template Changes


##  VLE Recipes


### Logged in

10-05-2017, Spec Change. recipeVersion depricated, replaced with version.

3-05-2017, Documentation change [RecipeVersion is the version of the collection of all Statements, removed revision number](https://github.co7/jiscdev/xapi/issues/154)

2-05-2016, Documentation change [subType supersedes ApplicationType](https://github.com/jiscdev/xapi/issues/55) in objectA


### Logged out

10-05-2017, Spec Change. recipeVersion deprecated, replaced with version

3-05-2017, Documentation change [RecipeVersion is the version of the collection of all Statements, removed revision number](https://github.com/jiscdev/xapi/issues/154)

20-03-2017, Spec change. [Description no longer required in ObjectA.](https://github.com/jiscdev/xapi/issues/148)

2-05-2016, Documentation change [subType supersedes ApplicationType](https://github.com/jiscdev/xapi/issues/55) in objectA


### VLE resource viewed

06-07-2017, Spec Change. [id removed from CourseArea](https://github.com/jiscdev/xapi/issues/179)

25-05-2017, Documentation change. [subType did not make sense](https://github.com/jiscdev/xapi/issues/163)

25-05-2017, Spec Change. [UDD Mod ID added to coursearea](https://github.com/jiscdev/xapi/issues/165)

10-05-2017, Spec Change. recipeVersion deprecated, replaced with version

3-05-2017, Documentation change [RecipeVersion is the version of the collection of all statements, removed revision number](https://github.com/jiscdev/xapi/issues/154)

11-04-2017, Documentation change [added subType example to documentation]

20-03-2017, Spec change. [Description no longer required in ObjectA.](https://github.com/jiscdev/xapi/issues/148)

2-05-2016, Documentation change [subType supersedes ApplicationType](https://github.com/jiscdev/xapi/issues/55)


### Session timeout

20-06-2017, Spec Change. [deprecated](https://github.com/jiscdev/xapi/issues/170)

10-05-2017, Spec Change. recipeVersion deprecated, replaced with version

3-05-2017, Documentation change [RecipeVersion is the version of the collection of all Statements, removed revision number](https://github.com/jiscdev/xapi/issues/154)

20-03-2017, Spec Change. [Description no longer required in ObjectA.](https://github.com/jiscdev/xapi/issues/148)

2-05-2016, Documentation change [subType supersedes ApplicationType](https://github.com/jiscdev/xapi/issues/55)


#### Assignment Graded


06-07-2017, Spec Change. [id removed from CourseArea](https://github.com/jiscdev/xapi/issues/179)

20-06-2017, Spec Change. [Context.ContextActivities removed. Template uses contextA instead of A](https://github.com/jiscdev/xapi/issues/168)

25-05-2017, Spec Change. [UDD Mod ID added to courseArea](https://github.com/jiscdev/xapi/issues/165)

10-05-2017, Spec Change. recipeVersion deprecated, replaced with version

3-05-2017, Documentation change [RecipeVersion is the version of the collection of all Statements, removed revision number](https://github.com/jiscdev/xapi/issues/154)

20-04-2017, Documentation Change. SubType example in context.contextActivities (which is an Object that fits ObjectA statement).

11-04-2017, Documentation Change. [Description no longer required in ObjectA or B.](https://github.com/jiscdev/xapi/issues/148)

20-03-2017, Spec change. [Description no longer required in ObjectA or B.](https://github.com/jiscdev/xapi/issues/148)


#### Assignment Submitted

06-07-2017, Spec Change. [id removed from courseArea](https://github.com/jiscdev/xapi/issues/179)

20-06-2017, Spec Change. [Context.ContextActivities removed. Template uses ContextA instead of A](https://github.com/jiscdev/xapi/issues/168)

25-05-2017, Spec Change. [UDD Mod ID added to courseArea](https://github.com/jiscdev/xapi/issues/165)

10-05-2017, Spec Change. recipeVersion deprecated, replaced with version

3-05-2017, Documentation change [RecipeVersion is the version of the collection of all Statements, removed revision number](https://github.com/jiscdev/xapi/issues/154)

20-04-2017, Documentation change. SubType example in context.contextActivities (which is an Object that fits ObjectA statement).

11-04-2017, Documentation change. [Description no longer required in ObjectA.](https://github.com/jiscdev/xapi/issues/148)

20-03-2017, Spec change. [Description no longer required in ObjectA.](https://github.com/jiscdev/xapi/issues/148). Removed from ObjectA in Context.


### Attendance Recipes



#### Attended learning activity

06-07-2017, Spec Change. [id removed from courseArea](https://github.com/jiscdev/xapi/issues/179)

25-05-2017, Doc Change. [Removed event_timetabled type from example, replaced with lecture. subType changed](https://github.com/jiscdev/xapi/issues/165)

25-05-2017, Spec Change. [added timetabled event extensions](https://github.com/jiscdev/xapi/issues/165)

25-05-2017, Spec Change. [courseArea added to context.extensions](https://github.com/jiscdev/xapi/issues/165)

25-05-2017, Spec Change. [UDD Mod ID added to courseArea](https://github.com/jiscdev/xapi/issues/165)

19/05/2017, Documentation change. [Remove event_timetabled uri trailing] /(https://github.com/jiscdev/xapi/issues/167)

10-05-2017, Spec Change. recipeVersion deprecated, replaced with version

9-05-2017, Spec Change. [DeviceLocation added to Context](https://github.com/jiscdev/xapi/issues/158)

3-05-2017, Documentation Change [RecipeVersion is the version of the collection of all Statements, removed revision number](https://github.com/jiscdev/xapi/issues/154)


10-04-2017

Spec change [Most context.extensions moved to object.extensions](https://github.com/jiscdev/xapi/issues/151)

Spec change [event_late and activity_category renamed to activity_late and attendance_category](https://github.com/jiscdev/xapi/issues/151)

Spec change [object.definition.type changed from event to event_timetabled](https://github.com/jiscdev/xapi/issues/151)

Spec change [context.extensions.http://xapi.jisc.ac.uk/activity_max_count and context.extensions.http://xapi.jisc.ac.uk/activity_mandatory changed to event_max_count and activity_mandatory](https://github.com/jiscdev/xapi/issues/151)


17-02-2017

Spec change [added http://xapi.jisc.ac.uk/attendance_category to results.extension](https://github.com/jiscdev/xapi/issues/142)

Spec change [http://xapi.jisc.ac.uk/activity_type_description added](https://github.com/jiscdev/xapi/issues/142)


08-02-2017

3-05-2016, Documentation change [RecipeVersion is the version of the collection of all Statements, removed revision number](https://github.com/jiscdev/xapi/issues/154)

Spec change [Attendance - change context to match VLE](https://github.com/jiscdev/xapi/issues/139)

Spec change [vle_mod_id and uddModInstanceID used in attendance](https://github.com/jiscdev/xapi/issues/140\)

Spec change [context.instructor.name removed atttendance](https://github.com/jiscdev/xapi/issues/141)

Spec change [added http://xapi.jisc.ac.uk/activity_type_id, http://xapi.jisc.ac.uk/activity_max_count and activity_mandatory to content extensions](https://github.com/jiscdev/xapi/issues/142)

Spec change [added http://xapi.jisc.ac.uk/activity_late to result.extensions](https://github.com/jiscdev/xapi/issues/142)

Documentation change [start time and end time replace duration](https://github.com/jiscdev/xapi/issues/143)


## Student App Recipes

### Mobile App Content Viewed 

25-05-2017, Spec Change. [UDD Mod ID added to courseArea](https://github.com/jiscdev/xapi/issues/165)


# Vocabulary Changes
Tracking identifier mappings between changes


## v1.0

19/06/07: [/file retired and covered by /content instead]


## v0.2

| V0.1  		| v0.2                    		 | 
| ------------- | -------------------------------|
| http://xapi.jisc.ac.uk/define/extensions/vle/content  | http://xapi.jisc.ac.uk/vle/content
| http://xapi.jisc.ac.uk/define/extensions/vle/page     | http://xapi.jisc.ac.uk/vle/page  
| http://xapi.jisc.ac.uk/define/extensions/vle/quiz     | http://xapi.jisc.ac.uk/vle/quiz  
| http://xapi.jisc.ac.uk/define/extensions/vle/forum    | http://xapi.jisc.ac.uk/vle/forum  
| http://xapi.jisc.ac.uk/define/extensions/externalURL  | http://xapi.jisc.ac.uk/externalURL
| http://xapi.jisc.ac.uk/extensions/courseArea | http://xapi.jisc.ac.uk/courseArea	
| http://xapi.jisc.ac.uk/extensions/sessionId  | http://xapi.jisc.ac.uk/sessionId 
| http://xapi.jisc.ac.uk/extensions/recipeVersion | http://xapi.jisc.ac.uk/recipeVersion
| http://xapi.jisc.ac.uk/extensions/applicationType | http://xapi.jisc.ac.uk/applicationType
| http://xapi.jisc.ac.uk/extensions/duedate  | http://xapi.jisc.ac.uk/dueDate
| http://xapi.jisc.ac.uk/define/vle   		 | http://id.tincanapi.com/activitytype/lms        
| http://www.tincanapi.co.uk/verbs/evaluated | http://adlnet.gov/expapi/verbs/scored 
