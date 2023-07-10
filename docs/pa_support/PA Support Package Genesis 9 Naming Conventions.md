# *Conventions*

Naming conventions for the files on Genesis 9 differ from Genesis 8 to
reduce the number of prefixes in use, and to force the sorting of morphs
into products more easily. This change was partially introduced in 8.1
with the facs additions, and fully changed with 9. It completely
replaces the previous PHM, PBM, FHM, FBM, MCM, pJCM, JCM, etc.

> **Regions:**

-   **head**

-   **body**

-   **figure**

-   **facs** (which is it's own category to separate all the expression
    controls into a single group type)

> **Types:**

-   **bs (blendshape)** any blendshape which is itself not intended to
    be a correction of something else.

-   **cbs (corrective blendshape)** any blendshape which is only
    intended to be a correction of something else.

-   **ctrl (controls)** a parameter dial which only controls other
    things, but has no blendshape data of its own.

> **Left or Right:**

-   Specified using l or r.

> **Negative or Positive:**

-   Specified using n or p.

**HD plus \#** simply to indicate the status of HD and a number to
indicate the DAZ Studio level of division. Note: DS starts counting from
0 not 1, unlike Zbrush.

# *Product Examples*

> **Character or Shaping:**

It should follow the naming conventions of the rest of the figure,
except with a prefix of the character name.

\<character/product name\>\_\<region\>\_\<parameter type\>\_\<parameter
name\> \<l/r\>\_\<HD#\> Victoria9_head_bs_Head

Victoria9_head_bs_Head_HD5

Victoria9_body_bs_Body Victoria9_body_bs_Body_HD5
Victoria9_figure_ctrl_Character Victoria9_figure_ctrl_Character_HD5
Victoria9_body_cbs_NipplesFeminine_HD5

or could be prefixed by a product name in cases where the end product is
not a character. For example:

Zev0BodyWorks_body_bs_ThighsToned01

> **Character Pose Corrective Blendshapes:**

These follow a similar naming pattern, but should add a section that
specifies the target pose being corrected.

That section would be named in the following pattern \<axis\>
\<degrees\> \<p/n\> (positive or negative)\>

Example corrective name: BaseFeminine_body_cbs_shin\_**x155p**\_l

Which correlates to the character name, body region, a corrective
blendshape, for the shin, X axis rotation 155 degrees positive, on the
left side.
