# Collaboration

This page describes:

- enabling collaboration on your (cloud based) project
- inviting members

## Sources

Dassault advices to follow:

- ["Cross-Company Collaboration or how to invite a user on your platform without consuming your license keys?"](https://r1132100503382-eu1-3dswym.3dexperience.3ds.com/#community:4/post:rHFgrLlQRr6w7xEwrVCYlA) (wiki, updated Feb 2019)

The author also found:

- ["3DEXPERIENCE Platform Administration: Adding users from outside your organization"](https://www.cati.com/blog/3dexperience-platform-administration-adding-users-from-outside-your-organization/) (blog, Mar 2021)

   This is a more readable version, and more current.

>Note: The process does apply to Solidworks for Makers as well, though the wiki page outdates its release by whole 2 years.


## Requirements

We expect you to have a Solidworks for Makers assembly, which is saved to 3DExperience (i.e. online).

- A friend maker (with Solidworks for Makers account) who's playing along
   - email address to such person; the one associated with their 3DExperience ID.

With these information you should be able to send an invite, and end up collaborating with the same Solidworks for Makers project.

Let's start!


<!-- disabled
## Dassault approach

Solidworks for Makers has no tools for collaboration. One cannot get a URL that one could share with friends, as an invite, to an online project. There is no "Invite" or "Collaborate" menu item, anywhere. `File` > `Publish...` looks inviting, but opens a file save dialog, instead.

This is so pre-cloud days.

This (cloud collaboration) could be handled in the 3DExperience side of things (for Solidworks for Makers projects). Unfortunately, the current (Sep 2022) model is **not built for makers** but for larger companies, instead.
-->


## Steps

### 0. Preparations (one time)

- 3DExperience Launcher > `Members` > `Configure Members Options`

   Enable this:
   
   ![](.images/enable-invitations.png)

<!-- ??
   - Ask "J" to do the same, on their account
-->

- Enable also:

   ![](.images/enable-invitations-from-members.png)

- Click `(select default roles to assign)` <!-- this step is not mentions in the Dassault wiki page -->

   - `View all` > check `3DEXPERIENCE SOLIDWORKS Professional`
   - clear the `Assign License` checks

      ![](.images/default-roles.png)
      
      Return to the `View selected roles only` page; it should now look like:
      
      ![](.images/default-roles-2.png)

   - `Save`

- Go to `Invite & Grant Roles` > `Invite members`.

   ![](.images/invite-members.png)

   - `User email`: fill the email of the invitee that is connected to their 3DExperience ID (or they'll register as such)
   
   - `User right`: `External`
   
      >This is explained in a third party [blog post](https://www.cati.com/blog/3dexperience-platform-administration-adding-users-from-outside-your-organization/) (Mar 2021), which says:
      >
      >>If the users are a part of your company and will be using your Roles you will select **Member** under User rights. If the users are bringing their own Roles to the Tenant, you will select **External**.

      <!-- tbd. If we know where Dassault documents these, add a link here. -->

- Proceed to `Roles`

   >There are **loads** of roles under "available" - and these are not really evan available for you. We can stick with the `Available roles with licenses` section.
   
   Check `3DEXPERIENCE SOLIDWORKS Professional`.
   
   ![](.images/invite-roles.png)
   
   >Note: Ignore the red "not enough licenses". It seems like a UX glitch.
   
   - `Next` 
   - `Invite`
   
**What you see**

- ![](.images/invite-pending.png)

**What the invitee receives**

- They get an email:

   ![](.images/invite-email.jpg)

   The email is sent from `noreply@3dexperience.3ds.com` and "Dassault Systèmes". The title doesn't mention you at all, which is a bit.. disappointing.
   
Pressing the link leads to 3DExperience login page, or registration if the person is new to 3DExperience.

*tbd. To be completed, once I have a partner to test this workflow with!*



   
   
   
   


<!-- disabled

## Feelings...

The author is not sold on the 3DSwym approach.

It might be a suitable solution for enterprise companies, doing a lot of CAD. For hobbyists, the interface is awkward, and Yet Another Tool to know.

Makers are often versed in collaboration tools. We judge these against Discord, and these tools *cannot* live to that standard.

A slimmed down approach, leaving out discussion forums (because we already have them) but focusing on access rights management, would entice the author.
-->

## References

- [3DExperience Tutorial - 3DSwym](https://www.youtube.com/watch?v=bBzx4eoeUiA) (Youtube 2:35, undated) [1]

   Shows a guy showing 3DSwym. Slow motion helps understand some aspects.
   
- ["Collaborating Remotely Using SOLIDWORKS: How to Do It Like the Pros"](https://blogs.solidworks.com/solidworksblog/2020/05/collaborating-remotely-using-solidworks-how-to-do-it-like-the-pros.html) (blog+video, May 2020)
