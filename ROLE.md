
English
====

Maintainer
----
* Continuously contribute code to any repo in swoole group for 1 year and its effective higher than 10 commit times, and can obtain the access to `admin/maintain/write` from the repo or its opposite team.
* Within 1 year effective commit times is zero, remove maintainer permission.

> Fix typo, fix grammar and wrong words, optimize error message, all above are not seen as effectual commit.  
> Add account to swoole group members as soon when get the access to maintainer

Owner
----
* Obtained maintainer permission, meanwhile offer code for 3 years to master branches of swoole-src, library repo, and annual effective commit times are greater than 100, This account should be upgraded from maintainer to owner
* Within 1 year effective commit times less than 10, cancel the owner permission and downgrade to maintainer.
* When group members only have 1 owner, the owner automatically becomes guard, not close the access until new maintainer upgrade to new owner

The swoole-src repository
-----
* Non-owner access account ,not directly submit code to branches of master, firstly provide pull request.(here in after referred to as PR)
* The `PR` couldn't merge to master until other maintainers review and agree, meanwhile, other owners obviously disagree.
* Big changes in owner's access account, must submit PR; not merge to master until other maintainer review and accept.
* Tiny changes in owner's access account, can directly submit to master, however other maintainers obviously make averse opinions, need to `revert commit` and  restart a new process.
* If PR is not reviewed by other maintainers beyond 3 days, then the operator self merge to master.

Friendly cooperation
----
* Don't submit malicious content: virus, erotic, violent, politically sensitive, abusive code are forbidden apart from malicious overwriting of ohters' commit code.
* Don't verbally attack, abuse or hurt other members and contributors.
* Any account that violates the terms of friendly cooperation will remove all permissions and be removed from the swoole group members.


中文
====

1 maintainer
-----
* 1.1 持续 `1` 年向 `swoole group` 任意仓库贡献代码，并且有效 `commit` 次数高于 `10`，可以获得该仓库或对应 `team` 的 `admin/maintain/write` 操作权限 (以下简称 `maintainer` )
* 1.2 近 `1` 年内有效 `commit` 次数等于 `0` 时，移除 `maintainer` 权限

> 修复拼写错误、优化错误信息、修复语法词法问题不计为有效 `commit`  
> 获得 `maintainer` 权限后会将此账户添加到 `swoole group members`  

2 owner
-----

* 2.1 拥有 `maintainer` 权限，并且持续 `3` 年向 `swoole-src`、`library` 两个核心仓库主分支贡献代码，每年有效 `commit` 次数高于 `100` 可以获得 `owner` 权限
* 2.2 近 `1` 年内有效 `commit` 次数低于 `10`，移除 `owner` 权限，降级为 `maintainer` 权限
* 2.2 当 `members` 中只有最后一个 `owner` 时，该 `owner` 自动成为看守者，不移除 `owner` 权限，直到有新的 `maintainer` 符合条件 `1` 成为新的 `owner`

3 swoole-src 仓库
-----
* 3.1 非 `owner` 权限账户，不直接向 master 分支提交代码，需要先提交 `pull request` (以下简称`PR`)
* 3.2 非 `owner` 权限账户 `PR` 经过其他 `maintainer` `review` 并同意后并且没有其他 `owner` 明确反对的情况下才可以 `merge` 到 `master`
* 3.3 `owner` 权限账户重大变更必须提交 `PR`，经过其他 `maintainer` `review` 并且接受后才可以 merge 到 `master`
* 3.4 `owner` 权限账户认为是轻微修改而直接提交到 `master`，其他 `maintainer` 明确提出反对意见，则需要要 `revert commit`，并按照第三条约定重新发起流程
* 3.5 若 `PR` 在超过 `3` 天以上时间没有其他 `maintainer` 进行 `review`，发起者可以将此 `PR` 自行合并到 `master`

4 PECL 账户
----
* 4.1 `swoole-src` 和 `library` 仓库的 `maintainer` 可以将添加到 `PECL` 开发者列表中，`owner` 可作为 `lead` 角色，`maintainer` 作为 `developer` 角色
* 4.2 近 `3` 年内不活跃的 `owner`（`lead` 角色）（参考 2.1 和 2.2）将 `active` 修改为 `no`
* 4.3 近 `1` 年内不活跃的 `maintainer`（`developer` 角色）（参考 1.1 和 1.2）将 `active` 修改为 `no`
* 4.4 违反第 `5` 条友好合作规定的账户，立即从 `PECL package.xml` 中删除

5 友好合作
-----
* 5.1 不得恶意提交代码，如：提交存在病毒的代码，恶意覆盖其他人的 `commit` 代码，提交带有色情、暴力、政治敏感、辱骂攻击他人等恶意的内容，包括代码、文档、注释、评论、`Issue`等
* 5.2 不对他人进行语言攻击，不得辱骂、伤害其他 `member`、`contributor`
* 5.3 违反友好合作条款的账户应立即移除一切权限，并从 `swoole group members` 中移除
