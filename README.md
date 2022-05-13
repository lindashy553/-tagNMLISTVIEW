# -tagNMLISTVIEW
Case $hListView_Right Switch $iCode Case $LVN_HOTTRACK Local $tInfo = DllStructCreate($tagNMLISTVIEW, $lParam) If $tInfo.Item = 5 And $tInfo.SubItem = 2 Then ToolTip("Infos displayed here...")
