### 游戏提示

###### 调用其Show（）方法时，工具提示会自动调整大小。有关详细信息，请参阅[GameTooltip对象信息](https://wow.gamepedia.com/UIOBJECT_GameTooltip)。

###### 游戏提示具有[UIObject](https://wow.gamepedia.com/Widget_API#UIObject)，[Region](https://wow.gamepedia.com/Widget_API#Region)和[Frame](https://wow.gamepedia.com/Widget_API#Frame)的所有方法，以及以下内容：

[GameTooltip:AddDoubleLine](https://wow.gamepedia.com/API_GameTooltip_AddDoubleLine)\(textL, textR, rL, gL, bL, rR, gR, bR\)

GameTooltip:AddFontStrings\(leftstring, rightstring\) - Dynamically expands the size of a tooltip - New in 1.11.

[GameTooltip:AddLine](https://wow.gamepedia.com/API_GameTooltip_AddLine)\("tooltipText" \[, textColor.r, textColor.g, textColor.b \[, wrapText\]\]\) - Appends the new line to the tooltip.

GameTooltip:AddSpellByID\(spellID\) -

[GameTooltip:AddTexture](https://wow.gamepedia.com/API_GameTooltip_AddTexture)\("texture"\) - Add a texture to the last line added.

GameTooltip:AdvanceSecondaryCompareItem\(\) -

GameTooltip:AppendText\("text"\) - Append text to the end of the first line of the tooltip.

[GameTooltip:ClearLines](https://wow.gamepedia.com/API_GameTooltip_ClearLines)\(\) - Clear all lines of tooltip \(both left and right ones\)

[GameTooltip:FadeOut](https://wow.gamepedia.com/API_GameTooltip_FadeOut)\(\) -

GameTooltip:GetAnchorType\(\) - Returns the current anchoring type.

[GameTooltip:GetItem](https://wow.gamepedia.com/API_GameTooltip_GetItem)\(\) - Returns name, link.

GameTooltip:GetMinimumWidth\(\) -

GameTooltip:GetOwner\(\) - Returns owner frame, anchor.

GameTooltip:GetPadding\(\) -

[GameTooltip:GetSpell](https://wow.gamepedia.com/API_GameTooltip_GetSpell)\(\) - Returns name, rank, id.

GameTooltip:GetUnit\(\) - Returns unit name, unit id.

GameTooltip:IsEquippedItem\(\) -

GameTooltip:IsUnit\("unit"\) - Returns bool.

[GameTooltip:NumLines](https://wow.gamepedia.com/API_GameTooltip_NumLines)\(\) - Get the number of lines in the tooltip.

GameTooltip:ResetSecondaryCompareItem\(\) -

GameTooltip:SetAchievementByID\(id\) -

[GameTooltip:SetAction](https://wow.gamepedia.com/API_GameTooltip_SetAction)\(slot\) - Shows the tooltip for the specified action button.

GameTooltip:SetAnchorType\(anchorType \[,Xoffset\] \[,Yoffset\]\) -

GameTooltip:SetAuctionCompareItem\("type", index\[, offset\]\)

GameTooltip:SetAuctionItem\("type", index\) - Shows the tooltip for the specified auction item.

[GameTooltip:SetAuctionSellItem](https://wow.gamepedia.com/API_GameTooltip_SetAuctionSellItem)\(\) -

GameTooltip:SetBackpackToken\(id\) -

[GameTooltip:SetBagItem](https://wow.gamepedia.com/API_GameTooltip_SetBagItem)\(bag, slot\) -

GameTooltip:SetBuybackItem\(slot\) -

GameTooltip:SetCompareItem\(shoppingTooltipTwo, primaryMouseover\) -

GameTooltip:SetCurrencyByID\(id\) -

[GameTooltip:SetCurrencyToken](https://wow.gamepedia.com/API_GameTooltip_SetCurrencyToken)\(tokenId\) - Shows the tooltip for the specified token

GameTooltip:SetCurrencyTokenByID\(currencyID\) -

GameTooltip:SetEquipmentSet\(name\) - Shows details for the equipment manager set identified by name.

GameTooltip:SetExistingSocketGem\(index, \[toDestroy\]\) -

[GameTooltip:SetFrameStack](https://wow.gamepedia.com/API_GameTooltip_SetFrameStack)\(showhidden\) - Shows the mouseover frame stack, used for debugging.

GameTooltip:SetGlyph\(id\) -

GameTooltip:SetGlyphByID\(glyphID\) -

GameTooltip:SetGuildBankItem\(tab, id\) - Shows the tooltip for the specified guild bank item

GameTooltip:SetHeirloomByItemID\(itemID\) -

[GameTooltip:SetHyperlink](https://wow.gamepedia.com/API_GameTooltip_SetHyperlink)\("itemString" or "itemLink"\) - Changes the item which is displayed in the tooltip according to the passed argument.

REMOVED GameTooltip:SetHyperlinkCompareItem\("itemLink", index\) - Sets a comparison tooltip to show the index'th comparison item to the item specified as link. Will return a true value if there is an index'th comparison item \(index is 1 through 3\)

[GameTooltip:SetInboxItem](https://wow.gamepedia.com/API_GameTooltip_SetInboxItem)\(index\) - Shows the tooltip for the specified mail inbox item.

GameTooltip:SetInstanceLockEncountersComplete\(index\) -

[GameTooltip:SetInventoryItem](https://wow.gamepedia.com/API_GameTooltip_SetInventoryItem)\(unit, slot\[, nameOnly\]\)

GameTooltip:SetInventoryItemByID\(itemID\) -

GameTooltip:SetItemByID\(itemID\) - Shows the tooltip for a specified Item ID. \(added in 4.2.0.14002 along with the Encounter Journal\)

GameTooltip:SetLFGCompletionReward\(lootIndex\) -

GameTooltip:SetLFGDungeonReward\(dungeonID, lootIndex\) -

GameTooltip:SetLFGDungeonShortageReward\(dungeonID, shortageSeverity, lootIndex\)\) -

GameTooltip:SetLootCurrency\(lootSlot\) -

[GameTooltip:SetLootItem](https://wow.gamepedia.com/API_GameTooltip_SetLootItem)\(lootSlot\) -

GameTooltip:SetLootRollItem\(id\) - Shows the tooltip for the specified loot roll item.

REMOVED GameTooltip:SetMerchantCompareItem\("slot"\[, offset\]\)

GameTooltip:SetMerchantCostItem\(slot\) -

GameTooltip:SetMerchantItem\(merchantSlot\) -

GameTooltip:SetMinimumWidth\(width\) - \(Formerly SetMoneyWidth\)

GameTooltip:SetMissingLootItem\(index\) -

GameTooltip:SetMountBySpellID\(\) -

[GameTooltip:SetOwner](https://wow.gamepedia.com/API_GameTooltip_SetOwner)\(owner, "anchor"\[, +x, +y\]\) -

[GameTooltip:SetPadding](https://wow.gamepedia.com/API_GameTooltip_SetPadding)\(\) -

GameTooltip:SetPetAction\(slot\) - Shows the tooltip for the specified pet action.

GameTooltip:SetPossession\(slot\) -

GameTooltip:SetPvPReward\(ID, isCurrency\) -

GameTooltip:SetQuestCurrency\("type", index\) -

GameTooltip:SetQuestItem\("type", index\) -

GameTooltip:SetQuestLogCurrency\("type", index\) -

GameTooltip:SetQuestLogItem\("type", index\)

GameTooltip:SetQuestLogRewardSpell - Shows the tooltip for the spell reward of the currently selected quest.

GameTooltip:SetQuestLogSpecialItem\(index\) -

GameTooltip:SetQuestRewardSpell

REMOVED [GameTooltip:SetReforgeItem](https://wow.gamepedia.com/API_GameTooltip_SetReforgeItem) - Shows the tooltip for the [reforge item](https://wow.gamepedia.com/API_GetReforgeItemInfo)

GameTooltip:SetSendMailItem\(\) -

GameTooltip:SetShapeshift\(slot\) - Shows the tooltip for the specified shapeshift form.

GameTooltip:SetSocketedItem\(\) -

GameTooltip:SetSocketGem\(index\) -

[GameTooltip:SetSpellBookItem](https://wow.gamepedia.com/API_GameTooltip_SetSpellBookItem)\(spellId, bookType\) - Shows the tooltip for the specified spell in the spellbook.

GameTooltip:SetSpellByID\(spellId\) - Shows the tooltip for the specified spell by global spell ID.

[GameTooltip:SetTalent](https://wow.gamepedia.com/API_GameTooltip_SetTalent)\(talentIndex \[, isInspect, talentGroup, inspectedUnit, classId\]\) - Shows the tooltip for the specified talent.

[GameTooltip:SetText](https://wow.gamepedia.com/API_GameTooltip_SetText)\("text", r, g, b\[, alphaValue\[, textWrap\]\]\) - Set the text of the tooltip.

GameTooltip:SetTotem\(slot\) -

GameTooltip:SetToyByItemID\(itemID\) -

REMOVED GameTooltip:SetTracking

GameTooltip:SetTradePlayerItem\(tradeSlot\) -

[GameTooltip:SetTradeSkillItem](https://wow.gamepedia.com/API_GameTooltip_SetTradeSkillItem)\(index \[,reagent\]\) -

GameTooltip:SetTradeTargetItem\(tradeSlot\) -

GameTooltip:SetTrainerService\(index\) -

[GameTooltip:SetTransmogrifyItem](https://wow.gamepedia.com/API_GameTooltip_SetTransmogrifyItem)\(slotId\) - Shows the tooltip when there is a pending \(de\)transmogrification

[GameTooltip:SetUnit](https://wow.gamepedia.com/API_GameTooltip_SetUnit) - Shows the tooltip for a particular unit

[GameTooltip:SetUnitAura](https://wow.gamepedia.com/API_GameTooltip_SetUnitAura)\("[unitId](https://wow.gamepedia.com/UnitId)", auraIndex\[, filter\]\) - Shows the tooltip for a unit's aura. \(Exclusive to 3.x.x / WotLK\)

[GameTooltip:SetUnitBuff](https://wow.gamepedia.com/API_GameTooltip_SetUnitBuff)\("[unitId](https://wow.gamepedia.com/UnitId)", buffIndex\[, raidFilter\]\) - Shows the tooltip for a unit's buff.

[GameTooltip:SetUnitConsolidatedBuff](https://wow.gamepedia.com/API_GameTooltip_SetUnitConsolidatedBuff)\("unit", buffIndex\) -

[GameTooltip:SetUnitDebuff](https://wow.gamepedia.com/API_GameTooltip_SetUnitDebuff)\("[unitId](https://wow.gamepedia.com/UnitId)", buffIndex\[, raidFilter\]\) - Shows the tooltip for a unit's debuff.

[GameTooltip:SetUpgradeItem](https://wow.gamepedia.com/API_GameTooltip_SetUpgradeItem)\(\) -

GameTooltip:SetVoidDepositItem\(slotIndex\) - Shows the tooltip for the specified Void Transfer [deposit slot](https://wow.gamepedia.com/API_GetVoidTransferDepositInfo) \(added in 4.3.0\)

GameTooltip:SetVoidItem\(slotIndex\) - Shows the tooltip for the specified Void Storage [slot](https://wow.gamepedia.com/API_GetVoidItemInfo) \(added in 4.3.0\)

GameTooltip:SetVoidWithdrawalItem\(slotIndex\) - Shows the tooltip for the specified Void Transfer [withdrawal slot](https://wow.gamepedia.com/API_GetVoidTransferWithdrawalInfo) \(added in 4.3.0\)

