# hanzi convert to pinyin and pinyin search

##实现功能
###1汉字转拼音
###2拼音转汉字
###3同音字/词模糊查询


实现方式比较粗糙,具体可根据场景和词频作优先级优化

var hanzisearch=require('hanzitopinyin');

hanzisearch.ToPinyin("小");

hanzisearch.ToHanZi("da"));

hanzisearch.getAllLikeNames("小明"));


