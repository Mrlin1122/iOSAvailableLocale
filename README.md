# iOSAvailableLocale

Following codes can dump all available locales in iOS.

    NSArray *localesStrs = [[NSArray alloc] initWithArray:[NSLocale availableLocaleIdentifiers]];
    for (NSString *localeStr in localesStrs)
    {
        NSLocale *locale = [[NSLocale alloc] initWithLocaleIdentifier:localeStr];
        NSString *countryCode = [locale objectForKey: NSLocaleCountryCode];
        NSLocale *usLocale = [[NSLocale alloc] initWithLocaleIdentifier:@"en_US"];
        NSString *country = [usLocale displayNameForKey: NSLocaleCountryCode value: countryCode];
        
        NSLog(@"%@ [%@]", localeStr, country);
    }

Following is all available locale with country name in iOS 8.

en_ZM [Zambia]
mn_Cyrl_MN [Mongolia]
eu 
ar_TD [Chad]
ja_JP [Japan]
mer_KE [Kenya]
ar 
en_KE [Kenya]
as 
ln_CG [Congo - Brazzaville]
ar_IL [Israel]
saq_KE [Kenya]
fur_IT [Italy]
en_CY [Cyprus]
es_GT [Guatemala]
ksb_TZ [Tanzania]
lt_LT [Lithuania]
es_UY [Uruguay]
sw_UG [Uganda]
ar_SA [Saudi Arabia]
en_NR [Nauru]
ar_LY [Libya]
es_PE [Peru]
az 
shi_Tfng_MA [Morocco]
en_CZ [Czech Republic]
vun_TZ [Tanzania]
gsw 
ii_CN [China]
agq_CM [Cameroon]
dyo 
vai_Latn_LR [Liberia]
ee_TG [Togo]
en_MO [Macau SAR China]
kk_Cyrl_KZ [Kazakhstan]
ca_IT [Italy]
tzm_Latn 
en_BW [Botswana]
en_AS [American Samoa]
gsw_LI [Liechtenstein]
vai_Vaii_LR [Liberia]
bas_CM [Cameroon]
en_MP [Northern Mariana Islands]
jgo_CM [Cameroon]
ar_KW [Kuwait]
zu_ZA [South Africa]
am_ET [Ethiopia]
nyn 
en_AT [Austria]
fr_VU [Vanuatu]
ee_GH [Ghana]
ta_IN [India]
fr_RE [Réunion]
ar_SD [Sudan]
tr_CY [Cyprus]
en_NU [Niue]
vai_Vaii 
es_PH [Philippines]
en_KI [Kiribati]
en_JE [Jersey]
en_AU [Australia]
be_BY [Belarus]
fr_TN [Tunisia]
fa_AF [Afghanistan]
ar_IQ [Iraq]
fr_GN [Guinea]
sk_SK [Slovakia]
dyo_SN [Senegal]
zh_Hant_HK [Hong Kong SAR China]
ar_ [World]
en_BZ [Belize]
ru_KZ [Kazakhstan]
en_VC [St. Vincent & Grenadines]
asa_TZ [Tanzania]
nl_AW [Aruba]
gd_GB [United Kingdom]
ha_Latn_GH [Ghana]
se_NO [Norway]
es_SV [El Salvador]
pt_PT [Portugal]
en_MS [Montserrat]
iu_Cans 
ko_KP [North Korea]
zh_Hans_CN [China]
ta 
te 
en_MT [Malta]
fr_HT [Haiti]
tg 
fr_GP [Guadeloupe]
kea 
tk_Latn 
pa 
th 
pa_Arab_PK [Pakistan]
ti 
es_ES [Spain]
nd_ZW [Zimbabwe]
es_DO [Dominican Republic]
tk 
ms_Latn_SG [Singapore]
zh_Hans_SG [Singapore]
yo_BJ [Benin]
en_MU [Mauritius]
ko_KR [South Korea]
lb 
fr_GQ [Equatorial Guinea]
en_IE [Ireland]
ta_SG [Singapore]
to 
yo_NG [Nigeria]
fr_CA [Canada]
pt_CV [Cape Verde]
kde_TZ [Tanzania]
pt_BR [Brazil]
es_CL [Chile]
fr_SN [Senegal]
ga_IE [Ireland]
uz_Arab 
pl 
tr 
bem 
ha 
ckb 
en_NZ [New Zealand]
lg 
ar_QA [Qatar]
en_LR [Liberia]
en_KN [St. Kitts & Nevis]
kw_GB [United Kingdom]
en_ZW [Zimbabwe]
sr_Cyrl_XK [Kosovo]
he 
kk_Cyrl 
ff_GN [Guinea]
pt_AO [Angola]
en_VG [British Virgin Islands]
ky_Cyrl 
ar_TN [Tunisia]
lkt_US [United States]
da 
ps 
en_MW [Malawi]
pt 
ckb_IQ [Iraq]
ln 
hi 
lo 
ebu 
en_LS [Lesotho]
te_IN [India]
de 
seh 
iu_Cans_CA [Canada]
hu_HU [Hungary]
shi_Latn 
lt 
sq_AL [Albania]
de_LI [Liechtenstein]
lu 
en_LT [Lithuania]
sr_Latn_XK [Kosovo]
lv 
kln_KE [Kenya]
ses_ML [Mali]
sbp 
gsw_FR [France]
ar_EG [Egypt]
fr_CD [Congo - Kinshasa]
hr 
en_VI [U.S. Virgin Islands]
es_CO [Colombia]
ne_NP [Nepal]
cs_CZ [Czech Republic]
chr 
hu 
ms_Latn_BN [Brunei]
ckb_IR [Iran]
el_GR [Greece]
en_MY [Malaysia]
en_LU [Luxembourg]
kab_DZ [Algeria]
en_JM [Jamaica]
mer 
shi 
ca_FR [France]
ar_EH [Western Sahara]
bez 
lo_LA [Laos]
kkj 
hy 
en_ [World]
teo 
fr_PF [French Polynesia]
bs_Latn 
is_IS [Iceland]
khq 
en_LV [Latvia]
ff_SN [Senegal]
pt_MO [Macau SAR China]
es_NI [Nicaragua]
fr_FR [France]
en_GB [United Kingdom]
fy_NL [Netherlands]
af_NA [Namibia]
sq_MK [Macedonia]
fr_DJ [Djibouti]
fr_CF [Central African Republic]
shi_Tfng 
dz 
ses 
en_UG [Uganda]
xog_UG [Uganda]
en_TC [Turks & Caicos Islands]
yav_CM [Cameroon]
nnh 
es_PR [Puerto Rico]
de_AT [Austria]
gu_IN [India]
fr_CG [Congo - Brazzaville]
es_CR [Costa Rica]
ur_PK [Pakistan]
ar_SO [Somalia]
mr_IN [India]
bs_Cyrl 
vi_VN [Vietnam]
en_IL [Israel]
en_GD [Grenada]
fr_CH [Switzerland]
lkt 
es_BO [Bolivia]
so_SO [Somalia]
hr_HR [Croatia]
bg_BG [Bulgaria]
en_IM [Isle of Man]
ln_AO [Angola]
si_LK [Sri Lanka]
sr_Latn 
fr_CI [Côte d’Ivoire]
fr_BE [Belgium]
it_IT [Italy]
en_SB [Solomon Islands]
as_IN [India]
teo_KE [Kenya]
af_ZA [South Africa]
en_IN [India]
ca_ES [Spain]
fr_BF [Burkina Faso]
en_WS [Samoa]
es_CU [Cuba]
en_SC [Seychelles]
ak_GH [Ghana]
sl_SI [Slovenia]
fr_NC [New Caledonia]
brx_IN [India]
en_IO [British Indian Ocean Territory]
en_HK [Hong Kong SAR China]
en_GG [Guernsey]
ms_Latn 
teo_UG [Uganda]
ar_DJ [Djibouti]
ewo 
sg_CF [Central African Republic]
ca_AD [Andorra]
sw_CD [Congo - Kinshasa]
ar_SS [South Sudan]
en_SD [Sudan]
nb_NO [Norway]
rm_CH [Switzerland]
mas_KE [Kenya]
en_GH [Ghana]
dav_KE [Kenya]
en_ [Europe]
dsb_DE [Germany]
so_DJ [Djibouti]
fr_SY [Syria]
en_UM [U.S. Outlying Islands]
rwk 
kam_KE [Kenya]
en_SE [Sweden]
fr_PM [St. Pierre & Miquelon]
gl_ES [Spain]
bo_CN [China]
fr_NE [Niger]
fr_MA [Morocco]
en_KY [Cayman Islands]
se 
en_GI [Gibraltar]
sg 
fr_CM [Cameroon]
fr_BI [Burundi]
tg_Cyrl_TJ [Tajikistan]
si 
mn_Cyrl 
km_KH [Cambodia]
sq_XK [Kosovo]
sk 
es_PY [Paraguay]
it_SM [San Marino]
sl 
ka 
uz_Arab_AF [Afghanistan]
sn 
fr_BJ [Benin]
qu_EC [Ecuador]
so 
mas_TZ [Tanzania]
fr_RW [Rwanda]
en_TK [Tokelau]
dz_BT [Bhutan]
en_SG [Singapore]
twq 
sq 
mt_MT [Malta]
kok_IN [India]
fr_MC [Monaco]
az_Latn 
sr 
tzm 
ga 
lb_LU [Luxembourg]
om 
en_IS [Iceland]
ar_ER [Eritrea]
ki 
gd 
sv 
es_AR [Argentina]
kk 
en_SH [St. Helena]
sw 
kl 
de_LU [Luxembourg]
or 
ca 
km 
os 
mgo_CM [Cameroon]
en_IT [Italy]
kn 
hr_BA [Bosnia & Herzegovina]
ki_KE [Kenya]
ko 
kkj_CM [Cameroon]
fr_BL [St. Barthélemy]
en_VU [Vanuatu]
en_SI [Slovenia]
gl 
sw_TZ [Tanzania]
ks 
pt_MZ [Mozambique]
guz_KE [Kenya]
az_Cyrl 
ru_RU [Russia]
en_GM [Gambia]
en_FI [Finland]
en_EE [Estonia]
ar_BH [Bahrain]
kw 
shi_Latn_MA [Morocco]
pa_Guru_IN [India]
ar_SY [Syria]
ff_CM [Cameroon]
eu_ES [Spain]
ky 
ti_ER [Eritrea]
fr_MF [St. Martin]
ar_MA [Morocco]
ig_NG [Nigeria]
gu 
en_HR [Croatia]
gv 
en_FJ [Fiji]
so_ET [Ethiopia]
ar_AE [United Arab Emirates]
or_IN [India]
en_US [United States]
en_TO [Tonga]
cs 
en_SK [Slovakia]
hy_AM [Armenia]
bs_Cyrl_BA [Bosnia & Herzegovina]
fr_MG [Madagascar]
kl_GL [Greenland]
en_FK [Falkland Islands]
nn_NO [Norway]
mfe 
om_ET [Ethiopia]
cy 
dua_CM [Cameroon]
fil_PH [Philippines]
en_SL [Sierra Leone]
zh_Hans 
ti_ET [Ethiopia]
uz_Latn 
os_GE [Georgia]
ms_Arab_BN [Brunei]
es_IC [Canary Islands]
se_SE [Sweden]
ru_MD [Moldova]
da_GL [Greenland]
ms_Latn_MY [Malaysia]
ha_Latn_NE [Niger]
gv_IM [Isle of Man]
en_HU [Hungary]
en_FM [Micronesia]
zgh_MA [Morocco]
en_DE [Germany]
en_CA [Canada]
fil 
en_TR [Turkey]
it_CH [Switzerland]
es_VE [Venezuela]
ks_Arab_IN [India]
ar_OM [Oman]
ewo_CM [Cameroon]
en_GR [Greece]
fr_DZ [Algeria]
ne_IN [India]
bm_Latn 
ar_LB [Lebanon]
fo_FO [Faroe Islands]
en_DG [Diego Garcia]
sr_Cyrl 
en_CC [Cocos (Keeling) Islands]
zh_Hans_MO [Macau SAR China]
nus_SD [Sudan]
en_TT [Trinidad & Tobago]
zh_Hant 
dua 
ar_PS [Palestinian Territories]
fr_ML [Mali]
ml_IN [India]
qu_PE [Peru]
kln 
lv_LV [Latvia]
rof 
nl_SR [Suriname]
kok 
sr_Cyrl_RS [Serbia]
se_FI [Finland]
sv_AX [Åland Islands]
tr_TR [Turkey]
es_MX [Mexico]
zh 
en_GU [Guam]
mua 
ar_YE [Yemen]
en_BA [Bosnia & Herzegovina]
tzm_Latn_MA [Morocco]
en_TV [Tuvalu]
tg_Cyrl 
sn_ZW [Zimbabwe]
rwk_TZ [Tanzania]
bn_IN [India]
vi 
xog 
en_FR [France]
ksh_DE [Germany]
en_BB [Barbados]
nb 
en_SS [South Sudan]
pt_TL [Timor-Leste]
en_RO [Romania]
sr_Latn_RS [Serbia]
en_PG [Papua New Guinea]
zu 
nd 
ksf_CM [Cameroon]
naq_NA [Namibia]
ne 
ar_DZ [Algeria]
en_DK [Denmark]
ro_RO [Romania]
ja 
rm 
rn 
ro 
en_PH [Philippines]
luo_KE [Kenya]
seh_MZ [Mozambique]
el_CY [Cyprus]
nl 
brx 
fa 
en_CH [Switzerland]
nn 
az_Cyrl_AZ [Azerbaijan]
lu_CD [Congo - Kinshasa]
ru 
nl_BE [Belgium]
en_US_POSIX [United States]
fur 
fr_MQ [Martinique]
en_NA [Namibia]
rw 
ff 
luo 
my_MM [Myanmar (Burma)]
en_GY [Guyana]
fa_IR [Iran]
en_DM [Dominica]
en_BE [Belgium]
fi 
fr_WF [Wallis & Futuna]
en_TZ [Tanzania]
hsb_DE [Germany]
be 
sr_Cyrl_BA [Bosnia & Herzegovina]
fr_MR [Mauritania]
bg 
to_TO [Tonga]
cgg_UG [Uganda]
en_ER [Eritrea]
az_Latn_AZ [Azerbaijan]
rof_TZ [Tanzania]
fo 
nus 
uz_Cyrl_UZ [Uzbekistan]
vun 
ha_Latn_NG [Nigeria]
fr 
nl_SX [Sint Maarten]
en_PK [Pakistan]
ps_AF [Afghanistan]
bm 
bn 
so_KE [Kenya]
guz 
bo 
en_ES [Spain]
ka_GE [Georgia]
en_CK [Cook Islands]
rn_BI [Burundi]
ru_KG [Kyrgyzstan]
sr_Latn_BA [Bosnia & Herzegovina]
en_SX [Sint Maarten]
br 
da_DK [Denmark]
luy 
en_PL [Poland]
bs 
fy 
es_ [Latin America]
haw_US [United States]
pa_Guru 
sw_KE [Kenya]
gsw_CH [Switzerland]
de_DE [Germany]
om_KE [Kenya]
uz_Latn_UZ [Uzbekistan]
bs_Latn_BA [Bosnia & Herzegovina]
en_ZA [South Africa]
en_AD [Andorra]
sah_RU [Russia]
en_RU [Russia]
ms_Arab 
nyn_UG [Uganda]
fr_MU [Mauritius]
zh_Hans_HK [Hong Kong SAR China]
fr_KM [Comoros]
mgh_MZ [Mozambique]
nmg_CM [Cameroon]
kab 
dje_NE [Niger]
en_CM [Cameroon]
fi_FI [Finland]
ta_LK [Sri Lanka]
en_SZ [Swaziland]
kea_CV [Cape Verde]
en_PN [Pitcairn Islands]
ru_BY [Belarus]
wae_CH [Switzerland]
en_NF [Norfolk Island]
chr_US [United States]
jmc_TZ [Tanzania]
ff_MR [Mauritania]
uz_Cyrl 
bm_Latn_ML [Mali]
es_EA [Ceuta & Melilla]
pa_Arab 
en_RW [Rwanda]
lag 
sbp_TZ [Tanzania]
en_NG [Nigeria]
ar_MR [Mauritania]
fr_YT [Mayotte]
es_HN [Honduras]
kde 
en_AG [Antigua & Barbuda]
cgg 
lag_TZ [Tanzania]
bas 
ms_Arab_MY [Malaysia]
kam 
sah 
khq_ML [Mali]
wae 
rw_RW [Rwanda]
es_EC [Ecuador]
br_FR [France]
ro_MD [Moldova]
th_TH [Thailand]
ebu_KE [Kenya]
fr_LU [Luxembourg]
ug_Arab_CN [China]
en_ME [Montenegro]
dje 
hi_IN [India]
ru_UA [Ukraine]
sr_Cyrl_ME [Montenegro]
fr_GA [Gabon]
sv_SE [Sweden]
vai 
dav 
en_BM [Bermuda]
en_AI [Anguilla]
en_PR [Puerto Rico]
naq 
lg_UG [Uganda]
mgh 
ar_KM [Comoros]
ky_Cyrl_KG [Kyrgyzstan]
mas 
pt_GW [Guinea-Bissau]
ha_Latn 
agq 
mfe_MU [Mauritius]
haw 
yi 
smn_FI [Finland]
qu_BO [Bolivia]
nb_SJ [Svalbard & Jan Mayen]
tk_Latn_TM [Turkmenistan]
saq 
pt_ST [São Tomé & Príncipe]
ur_IN [India]
ug 
sr_Latn_ME [Montenegro]
en_MG [Madagascar]
jmc 
en_LC [St. Lucia]
ks_Arab 
twq_NE [Niger]
nl_NL [Netherlands]
nnh_CM [Cameroon]
yo 
zh_Hant_TW [Taiwan]
de_CH [Switzerland]
jgo 
uk 
fr_TD [Chad]
asa 
mua_CM [Cameroon]
es_US [United States]
en_PT [Portugal]
en_NL [Netherlands]
mgo 
en_MH [Marshall Islands]
bez_TZ [Tanzania]
de_BE [Belgium]
zgh 
vai_Latn 
dsb 
cy_GB [United Kingdom]
en_AL [Albania]
ur 
he_IL [Israel]
bo_IN [India]
nl_BQ [Caribbean Netherlands]
mg 
zh_Hant_MO [Macau SAR China]
nmg 
bem_ZM [Zambia]
id 
et_EE [Estonia]
hsb 
yav 
mk 
ml 
ig 
yi_ [World]
mn 
ksb 
uz 
sv_FI [Finland]
ii 
pl_PL [Poland]
qu 
ug_Arab 
es_PA [Panama]
ee 
mk_MK [Macedonia]
ln_CD [Congo - Kinshasa]
fr_GF [French Guiana]
luy_KE [Kenya]
mr 
es_GQ [Equatorial Guinea]
ms 
kn_IN [India]
nl_CW [Curaçao]
mt 
fr_TG [Togo]
fr_SC [Seychelles]
en_PW [Palau]
ksf 
en_NO [Norway]
uk_UA [Ukraine]
af 
el 
is 
ksh 
my 
en_BS [Bahamas]
en 
it 
ta_MY [Malaysia]
id_ID [Indonesia]
smn 
iu 
eo 
mg_MG [Madagascar]
os_RU [Russia]
ak 
ar_JO [Jordan]
ln_CF [Central African Republic]
am 
es 
bn_BD [Bangladesh]
et 
en_CX [Christmas Island]
