### 游戏提示

###### 调用其Show（）方法时，工具提示会自动调整大小。有关详细信息，请参阅[GameTooltip对象信息](https://wow.gamepedia.com/UIOBJECT_GameTooltip)。

###### 游戏提示具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)，[Region](https://wow.gamepedia.com/Widget_API#Region)和[Frame](https://wow.gamepedia.com/Widget_API#Frame)的所有方法，以及以下内容：

[GameTooltip:AddDoubleLine](https://wow.gamepedia.com/API_GameTooltip_AddDoubleLine)\(textL, textR, rL, gL, bL, rR, gR, bR\)

GameTooltip:AddFontStrings\(leftstring, rightstring\) - 动态扩展工具提示的大小 -  1.11中的新增功能。

[GameTooltip:AddLine](https://wow.gamepedia.com/API_GameTooltip_AddLine)\("tooltipText" \[, textColor.r, textColor.g, textColor.b \[, wrapText\]\]\) - 将新行添加到工具提示中。

GameTooltip:AddSpellByID\(spellID\) -

[GameTooltip:AddTexture](https://wow.gamepedia.com/API_GameTooltip_AddTexture)\("texture"\) - 在添加的最后一行添加纹理。

GameTooltip:AdvanceSecondaryCompareItem\(\) -

GameTooltip:AppendText\("text"\) - 将文本附加到工具提示第一行的末尾。

[GameTooltip:ClearLines](https://wow.gamepedia.com/API_GameTooltip_ClearLines)\(\) - 清除所有工具提示行（左右两行）

[GameTooltip:FadeOut](https://wow.gamepedia.com/API_GameTooltip_FadeOut)\(\) -

GameTooltip:GetAnchorType\(\) - 返回当前锚定类型。

[GameTooltip:GetItem](https://wow.gamepedia.com/API_GameTooltip_GetItem)\(\) - 返回名称，链接。

GameTooltip:GetMinimumWidth\(\) -

GameTooltip:GetOwner\(\) - 返回所有者框架，锚点。

GameTooltip:GetPadding\(\) -

[GameTooltip:GetSpell](https://wow.gamepedia.com/API_GameTooltip_GetSpell)\(\) - 返回name，rank，id。

GameTooltip:GetUnit\(\) - 返回 unit name, unit id.

GameTooltip:IsEquippedItem\(\) -

GameTooltip:IsUnit\("unit"\) - 返回布尔值.

[GameTooltip:NumLines](https://wow.gamepedia.com/API_GameTooltip_NumLines)\(\) - 获取工具提示中的行数。

GameTooltip:ResetSecondaryCompareItem\(\) -

GameTooltip:SetAchievementByID\(id\) -

[GameTooltip:SetAction](https://wow.gamepedia.com/API_GameTooltip_SetAction)\(slot\) - 显示指定操作按钮的工具提示。

GameTooltip:SetAnchorType\(anchorType \[,Xoffset\] \[,Yoffset\]\) -

GameTooltip:SetAuctionCompareItem\("type", index\[, offset\]\)

GameTooltip:SetAuctionItem\("type", index\) - 显示指定拍卖项目的工具提示。

[GameTooltip:SetAuctionSellItem](https://wow.gamepedia.com/API_GameTooltip_SetAuctionSellItem)\(\) -

GameTooltip:SetBackpackToken\(id\) -

[GameTooltip:SetBagItem](https://wow.gamepedia.com/API_GameTooltip_SetBagItem)\(bag, slot\) -

GameTooltip:SetBuybackItem\(slot\) -

GameTooltip:SetCompareItem\(shoppingTooltipTwo, primaryMouseover\) -

GameTooltip:SetCurrencyByID\(id\) -

[GameTooltip:SetCurrencyToken](https://wow.gamepedia.com/API_GameTooltip_SetCurrencyToken)\(tokenId\) - 显示指定标记的工具提示

GameTooltip:SetCurrencyTokenByID\(currencyID\) -

GameTooltip:SetEquipmentSet\(name\) - 显示按名称标识的设备管理器集的详细信息。

GameTooltip:SetExistingSocketGem\(index, \[toDestroy\]\) -

[GameTooltip:SetFrameStack](https://wow.gamepedia.com/API_GameTooltip_SetFrameStack)\(showhidden\) - 显示用于调试的鼠标悬停框架堆栈。

GameTooltip:SetGlyph\(id\) -

GameTooltip:SetGlyphByID\(glyphID\) -

GameTooltip:SetGuildBankItem\(tab, id\) - 显示指定公会银行项目的工具提示

GameTooltip:SetHeirloomByItemID\(itemID\) -

[GameTooltip:SetHyperlink](https://wow.gamepedia.com/API_GameTooltip_SetHyperlink)\("itemString" or "itemLink"\) - 根据传递的参数更改工具提示中显示的项目。

REMOVED GameTooltip:SetHyperlinkCompareItem\("itemLink", index\) - 设置比较工具提示以显示指定为链接的项目的索引比较项目。如果存在索引比较项（索引为1到3），则返回真值GameTooltip：SetInboxItem（index） - 显示指定邮件收件箱项的工具提示。

[GameTooltip:SetInboxItem](https://wow.gamepedia.com/API_GameTooltip_SetInboxItem)\(index\) - 显示指定邮件收件箱项的工具提示。

GameTooltip:SetInstanceLockEncountersComplete\(index\) -

[GameTooltip:SetInventoryItem](https://wow.gamepedia.com/API_GameTooltip_SetInventoryItem)\(unit, slot\[, nameOnly\]\)

GameTooltip:SetInventoryItemByID\(itemID\) -

GameTooltip:SetItemByID\(itemID\) - 显示指定项ID的工具提示。 \(added in [4.2.0.14002](http://github.com/tekkub/wow-ui-source/commit/bd6faf4e8ccc4138d3c686bf9ee361e20f4a6531#L48R641) along with the [Encounter Journal](https://wow.gamepedia.com/World_of_Warcraft_API#Encounter_Journal_Functions)\)

GameTooltip:SetLFGCompletionReward\(lootIndex\) -

GameTooltip:SetLFGDungeonReward\(dungeonID, lootIndex\) -

GameTooltip:SetLFGDungeonShortageReward\(dungeonID, shortageSeverity, lootIndex\)\) -

GameTooltip:SetLootCurrency\(lootSlot\) -

[GameTooltip:SetLootItem](https://wow.gamepedia.com/API_GameTooltip_SetLootItem)\(lootSlot\) -

GameTooltip:SetLootRollItem\(id\) - 显示指定的战利品卷项目的工具提示。

REMOVED GameTooltip:SetMerchantCompareItem\("slot"\[, offset\]\)

GameTooltip:SetMerchantCostItem\(slot\) -

GameTooltip:SetMerchantItem\(merchantSlot\) -

GameTooltip:SetMinimumWidth\(width\) - \(Formerly SetMoneyWidth\)

GameTooltip:SetMissingLootItem\(index\) -

GameTooltip:SetMountBySpellID\(\) -

[GameTooltip:SetOwner](https://wow.gamepedia.com/API_GameTooltip_SetOwner)\(owner, "anchor"\[, +x, +y\]\) -

[GameTooltip:SetPadding](https://wow.gamepedia.com/API_GameTooltip_SetPadding)\(\) -

GameTooltip:SetPetAction\(slot\) - 显示指定宠物动作的工具提示。

GameTooltip:SetPossession\(slot\) -

GameTooltip:SetPvPReward\(ID, isCurrency\) -

GameTooltip:SetQuestCurrency\("type", index\) -

GameTooltip:SetQuestItem\("type", index\) -

GameTooltip:SetQuestLogCurrency\("type", index\) -

GameTooltip:SetQuestLogItem\("type", index\)

GameTooltip:SetQuestLogRewardSpell - 显示当前所选任务的法术奖励的工具提示。

GameTooltip:SetQuestLogSpecialItem\(index\) -

GameTooltip:SetQuestRewardSpell

REMOVED [GameTooltip:SetReforgeItem](https://wow.gamepedia.com/API_GameTooltip_SetReforgeItem) - 显示[重新锻造项目](https://wow.gamepedia.com/API_GetReforgeItemInfo)的工具提示

GameTooltip:SetSendMailItem\(\) -

GameTooltip:SetShapeshift\(slot\) - 显示指定shapeshift表单的工具提示。

GameTooltip:SetSocketedItem\(\) -

GameTooltip:SetSocketGem\(index\) -

[GameTooltip:SetSpellBookItem](https://wow.gamepedia.com/API_GameTooltip_SetSpellBookItem)\(spellId, bookType\) -显示法术书中指定法术的工具提示。

GameTooltip:SetSpellByID\(spellId\) - 按全局拼写ID显示指定拼写的工具提示。

[GameTooltip:SetTalent](https://wow.gamepedia.com/API_GameTooltip_SetTalent)\(talentIndex \[, isInspect, talentGroup, inspectedUnit, classId\]\) - 显示指定天赋的工具提示。

[GameTooltip:SetText](https://wow.gamepedia.com/API_GameTooltip_SetText)\("text", r, g, b\[, alphaValue\[, textWrap\]\]\) - 设置工具提示的文本。

GameTooltip:SetTotem\(slot\) -

GameTooltip:SetToyByItemID\(itemID\) -

REMOVED GameTooltip:SetTracking

GameTooltip:SetTradePlayerItem\(tradeSlot\) -

[GameTooltip:SetTradeSkillItem](https://wow.gamepedia.com/API_GameTooltip_SetTradeSkillItem)\(index \[,reagent\]\) -

GameTooltip:SetTradeTargetItem\(tradeSlot\) -

GameTooltip:SetTrainerService\(index\) -

[GameTooltip:SetTransmogrifyItem](https://wow.gamepedia.com/API_GameTooltip_SetTransmogrifyItem)\(slotId\) - 在有（de\)变形时显示工具提示

[GameTooltip:SetUnit](https://wow.gamepedia.com/API_GameTooltip_SetUnit) - 显示特定单元的工具提示

[GameTooltip:SetUnitAura](https://wow.gamepedia.com/API_GameTooltip_SetUnitAura)\("[unitId](https://wow.gamepedia.com/UnitId)", auraIndex\[, filter\]\) - 显示单位光环的工具提示。（3.x.x / WLK独家）

[GameTooltip:SetUnitBuff](https://wow.gamepedia.com/API_GameTooltip_SetUnitBuff)\("[unitId](https://wow.gamepedia.com/UnitId)", buffIndex\[, raidFilter\]\) - 显示单位buff的工具提示。

[GameTooltip:SetUnitConsolidatedBuff](https://wow.gamepedia.com/API_GameTooltip_SetUnitConsolidatedBuff)\("unit", buffIndex\) -

[GameTooltip:SetUnitDebuff](https://wow.gamepedia.com/API_GameTooltip_SetUnitDebuff)\("[unitId](https://wow.gamepedia.com/UnitId)", buffIndex\[, raidFilter\]\) -显示单位debuff的工具提示。

[GameTooltip:SetUpgradeItem](https://wow.gamepedia.com/API_GameTooltip_SetUpgradeItem)\(\) -

GameTooltip:SetVoidDepositItem\(slotIndex\) - 显示指定的Void Transfer[存款槽](https://wow.gamepedia.com/API_GetVoidTransferDepositInfo)的工具提示（在4.3.0中添加）

GameTooltip:SetVoidItem\(slotIndex\) - 显示指定Void存储[槽](https://wow.gamepedia.com/API_GetVoidItemInfo)的工具提示（在4.3.0中添加）

GameTooltip:SetVoidWithdrawalItem\(slotIndex\) - 显示指定的Void Transfer[提取槽](https://wow.gamepedia.com/API_GetVoidTransferWithdrawalInfo)的工具提示（在4.3.0中添加）

