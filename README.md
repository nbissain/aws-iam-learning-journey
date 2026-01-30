# Lab 1: Introduction to AWS IAM

**Completed:** January 2026
**Platform:** AWS Training Lab

## Lab Objectives

- Understand IAM users, groups, and roles
- Create and manage IAM policies
- Apply least privilege principles

## What I Practiced

- Followed a real-world scenario, adding users to groups with specific capabilities enabled
- Inspected IAM policies as applied to the pre-created groups
- Tested permissiond to verify least privilege implementation
- Used IAM policy Simulator to validate access
- Experimented with the effects of policies on service access

## Key Learnings

1. **Policies vs. Permissions:** Understanding the difference between identity-based policies (attached to users/groups/roles) and resource-based policies was crucial
2. **Least Privilege in Action:** Startung with minimal permissions and adding onlywhat's necessary is more secure than granting broad access and restricting later
3. **Groups > Indivisual Users:** Managing permissions through groups is far more scalable and maintainable than attaching policies to individual users
4. **JSON Policy Structure:** Learning the anatomy of IAM policies (Effect, Action, Resource, Condition) makes creating custom policies much easier

