# xAPI recipes for the Jisc Learning Analytics Service v1.0

## Repository Workflow
The simplest way of contributing to the xAPI service works as follows:


1. Add an issue to the issue tracker to alert everyone to what you are working on and why.
2. Tag the issue with the version milestone you'd like the patch to be a part of.
3. If the feature is for this version then make an edit or add a file in this repository, and save it to your own branch. If you prefer, you can fork the whole repository and work in your own repository. Otherwise create a feature-branch to work in.
4. If you are creating a new Statement in a recipe then check if a generic template will help. If you are creating a new Statement then consider creating a generic one first.
4. Send a pull request once you're done.
5. The pull request will be discussed at one of our regular meetings and either merged, or kept in the queue, depending on whether more work is required.

You can do all this through the Github GUI, but you're welcome to use any other git tool you prefer.

If the need arises, particular versions will get their own branches, but until that time, everything is merged into the main branch. Releases will be made after the group has come to an agreement.

## Statement Vocabulary and Common Structures

* [Vocabulary](vocabulary.md) gives the IRIs and definitions for Verbs, Activity types, and so on, as well as for extensions used in the recipes.
* [Common Structures](common_structures.md) outlines common patterns used across different recipes.
* [Generic Statement Templates](generic/index.md) can be found in this directory.

# Recipes
Here are descriptions of Statements that can be sent to the Jisc Learning Records Warehouse, full Statement examples, data needed to create the Statement.  As far as possible all entities are the same across all the Statements.

## VLE

These are platform independent Statements related to Virtual Learning Enviroments. JSON examples are generated from plugins. Bug reports can be directed to the [Moodle](https://github.com/jiscdev/jisc-moodle-xapi-plugin) or [BlackBoard](https://github.com/jiscdev/blackboard-xapi-plugin) Github repository.

<table>
<tr><td>Statement Template </td>   <td>JSON example</td> </tr>
<tr><td> <a href = "/recipes/vle/login.md">Logged in</a></td><td> <a href = "vle/moodle/login.js">Logged in Moodle </a> <br/><a href = "vle/blackboard/loggedin.json"> Logged In Blackboard   </a>   </td> </tr>                                                           
<tr><td> <a href = "/recipes/vle/logout.md">Logged out</a></td><td> <a href = "vle/moodle/logout.js">Logged out Moodle </a>  <br/> <a href = "vle/blackboard/loggedout.json"> Logged out Blackboard   </a>    </td> </tr>    
<tr><td> <a href = "/recipes/vle/Module-View.md">VLE resource viewed   </a></td><td><a href = "vle/moodle/moduleview.js">Moodle module viewed </a> <br/> <a href = "vle/blackboard/course_access.json"> Blackboard course acccess  </a> <br/> <a href="vle/blackboard/course_content_access.json">Blackboard content accessed</a></td> </tr>    
<tr><td> <a href =  "/recipes/vle/assignment-graded.md">Assignment Graded   </a></td><td> <a href = "vle/moodle/asssignment_graded.json">Assignment graded in Moodle</a><br/> <a href="vle/blackboard/asssignment_graded.json">Assignment graded in Blackboard </a>   </td></tr>    
<tr><td> <a href =  "/recipes/vle/assignment-submitted.md">Assignment Submitted  </a></td><td><a href = "vle/moodle/assignment_submitted.json">Assignment submitted in Moodle</a><br/> <a href="vle/blackboard/assignment_submitted.json">Assignment submitted in Blackboard</a>   </td></tr>                                                             
</table>


### All VLE Statement examples
* [Blackboard VLE samples](vle/blackboard/Examples.md)
* [Moodle VLE samples](vle/moodle/examples.md)

## Presence and Attendance
<table>
<tr><td>Statement Template </td><td>JSON Example</td></tr>
<tr><td> <a href = "recipes/attendance/attendance.md">Attended learning activity </a></td><td><a href = "recipes/attendance/attendance.md#example">Attended learning activity </a></td> </tr>    
</table>

## Predictive Model Output

<table>
<tr><td>Statement Template </td><td>JSON Example</td></tr>
<tr><td> <a href = "/lap/apereo/model_output.md">Predictive Model Alerting</a></td><td><a href = "/lap/apereo/model_output.js">Alerting JSON</a></td> </tr>    
</table>


# Deprecated Statements

- [Session timeout](/recipes/vle/Session-timeout.md)    

