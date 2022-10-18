<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="50"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="3fb06f3f-334a-412c-b5f3-def3e5470e24" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WIconBreadcrumb rel="" href="" icon="house-fill" text="House" scale="" shift="" v-bind:active="false"
        v-bind:isIcon="true" v-bind:options="[]" v-bind:disabled="false" v-bind:selected="[]" v-bind:isEnabled="true"
        linkTarget="_self" visibility="visible" ariaCurrent="location" ncTypography="body1" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#4285f4"
        ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#4285f4" ncHoverBorderColor="#4285f4"
        ncDisableBorderColor="transparent" ncClickBackgroundColor="#4285f4" ncFocusBackgroundColor="#4285f4"
        ncHoverBackgroundColor="#4285f4" ncDisableBackgroundColor="#969696" position="absolute" top="7.139240506329114%"
        left="26.067391304347826%" id="5dab6921-40fc-43df-8b91-ef49f3eca019"
        v-bind:style="{'color':'#007bff','width':'','height':'','fontSize':'9.008px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','background':'#e9ecef','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'0px','paddingTop':'5.629999999999999px','visibility':'visible','marginRight':'0px','paddingLeft':'5.629999999999999px','marginBottom':'0px','paddingRight':'5.629999999999999px','paddingBottom':'5.629999999999999px','textDecoration':'none','zIndex':2}"/>
      <WBlockquoteLabel text="— Author Name, Publication" theme="theme--light01" ncTypography="body1" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        position="absolute" top="16.949367088607595%" left="33.7695652173913%" id="5ed594a1-2b86-4945-b06b-74e6d757ef92"
        v-bind:style="{'color':'gray','width':'','height':'','fontSize':'6.755999999999999px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'0.7881999999999999','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':3}"/>
      <WButtonAvatar src="" href="" icon="" size="" text="" v-bind:badge="false" v-bind:button="true"
        v-bind:square="false" v-bind:rounded="false" variant="secondary" v-bind:badgeTop="false" v-bind:disabled="false"
        v-bind:badgeLeft="false" badgeText="" buttonText="Button Text Avatar" linkTarget="_self" ncLinkType="link"
        v-bind:aspectRatio="true" badgeOffset="" dataLoading="static" badgeVariant="primary" v-bind:hasDesignMode="true"
        ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'update':{'type':'dataModelForDynamicType'},'propName':'src','displayName':'Value'}]}"
        toForRouterLink="to" dataModelForDynamicType="string" position="absolute" top="19.319620253164558%"
        left="54.73913043478261%" id="163ddfee-962b-4c23-af7c-0fe22719a813"
        v-bind:style="{'width':'','height':'','maxWidth':'','minWidth':'','boxShadow':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':4}"/>
      <TwAvatar imgWidth="tw-w-9" linkHref="#" imgHeight="tw-h-9" imgRadius="tw-rounded-full"
        alignItems="tw-items-center" headerText="Tom Cook" headerColor="tw-text-gray-700"
        imageSource="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
        textDisplay="tw-sr-only" ncTooltipText="" paragraphText="View profile" headerFontSize="tw-text-sm"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imageSource','displayName':'Value'}]}"
        paragraphColor="tw-text-gray-500" headerFontFamily="tw-font-sans" headerFontWeight="tw-font-medium"
        headerHoverColor="tw-ring-2" notificationRing="tw-ring-2" notificationColor="tw-bg-gray-300"
        notificationWidth="tw-w-1.5" paragraphFontSize="tw-text-xs" notificationHeight="tw-h-1.5"
        notificationRadius="tw-rounded-3xl" notificationDisplay="tw-sr-only" paragraphFontFamily="tw-font-sans"
        paragraphFontWeight="tw-font-medium" paragraphHoverColor="tw-text-gray-700"
        notificationPosition="tw-top-0 tw-right-0" notificationRingColor="tw-ring-white" position="absolute"
        top="33.563291139240505%" left="39.790217391304346%" id="541c64df-eab1-48f2-9404-d91145cdc2df"
        v-bind:style="{'width':'28.15','height':'28.15','fontSize':'7.882px','maxWidth':'','minWidth':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','backgroundColor':'','zIndex':5}"/>
      <WAvatar src="" href="" icon="" size="" text="" v-bind:badge="false" v-bind:button="false" v-bind:square="false"
        v-bind:rounded="false" variant="secondary" v-bind:badgeTop="false" v-bind:disabled="false"
        v-bind:badgeLeft="false" badgeText="" buttonText="Button Text Avatar" linkTarget="_self" ncLinkType="link"
        v-bind:aspectRatio="true" badgeOffset="" dataLoading="static" badgeVariant="primary" v-bind:hasDesignMode="true"
        ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'update':{'type':'dataModelForDynamicType'},'propName':'src','displayName':'Value'}]}"
        toForRouterLink="to" dataModelForDynamicType="string" position="absolute" top="33.87658227848101%"
        left="54.25760869565217%" id="15c88a12-ca9f-49a5-951f-74c1584345e0"
        v-bind:style="{'width':'16.889999999999997px','height':'16.889999999999997px','maxWidth':'','minWidth':'','boxShadow':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':6}"/>
      <WWarningLinkAlert v-bind:fade="false" v-bind:pill="false" show="false" size="md" v-bind:isLink="true"
        v-bind:squared="false" hrefLink="" alertLabel="This alert will dismiss after time lapse" background="#17a2b8"
        buttonLabel="Show alert with count-down timer" v-bind:dismissible="false" alertVariant="warning"
        dismissLabel="Close" ncTypography="body1" verticalWidth="60px" buttonsVariant="warning"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'buttonLabel','displayName':'ButtonLabel'},{'type':'string','propName':'alertLabel','displayName':'AlertLabel'}]}"
        verticalHeight="60px" horizontalWidth="" progressVariant="warning" v-bind:dismissCountDown="5"
        horizontalHeight="" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
        ncClickBorderColor="#f9c108" ncFocusBorderColor="#f9c108" ncHoverBorderColor="#f9c108"
        ncClickBackgroundColor="#f9c108" ncFocusBackgroundColor="#f9c108" ncHoverBackgroundColor="#f9c108"
        position="absolute" top="16.957278481012658%" left="21.093478260869563%"
        id="156e433e-9b6a-4ffa-bf6c-24237965a4b6"
        v-bind:style="{'color':'#000000','width':'','height':'','fontSize':'9.008px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'225.2','lineHeight':'13.511999999999999px','marginLeft':'0px','paddingTop':'3.3779999999999997px','textShadow':'','visibility':'visible','borderColor':'#fdf3cd','borderStyle':'none','marginRight':'0px','paddingLeft':'6.755999999999999px','marginBottom':'0px','paddingRight':'6.755999999999999px','paddingBottom':'3.3779999999999997px','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':7}"/>
      <WSecondaryAlert v-bind:fade="false" v-bind:pill="false" show="false" size="md" v-bind:isLink="false"
        v-bind:squared="false" hrefLink="" alertLabel="This alert will dismiss after time lapse" background="#17a2b8"
        buttonLabel="Show alert with count-down timer" v-bind:dismissible="false" alertVariant="secondary"
        dismissLabel="Close" ncTypography="body1" verticalWidth="60px" buttonsVariant="secondary"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'buttonLabel','displayName':'ButtonLabel'},{'type':'string','propName':'alertLabel','displayName':'AlertLabel'}]}"
        verticalHeight="60px" horizontalWidth="" progressVariant="secondary" v-bind:dismissCountDown="5"
        horizontalHeight="" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
        ncClickBorderColor="#6c757d" ncFocusBorderColor="#6c757d" ncHoverBorderColor="#6c757d"
        ncClickBackgroundColor="#6c757d" ncFocusBackgroundColor="#6c757d" ncHoverBackgroundColor="#6c757d"
        position="absolute" top="31.507911392405063%" left="19.922826086956523%"
        id="179dc5a9-43ac-4876-8acc-2c870fe07136"
        v-bind:style="{'color':'#FFFFFF','width':'','height':'','fontSize':'9.008px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'225.2','lineHeight':'13.511999999999999px','marginLeft':'0px','paddingTop':'3.3779999999999997px','textShadow':'','visibility':'visible','borderColor':'#e2e3e5','borderStyle':'none','marginRight':'0px','paddingLeft':'6.755999999999999px','marginBottom':'0px','paddingRight':'6.755999999999999px','paddingBottom':'3.3779999999999997px','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':8}"/>
      <WPrimaryLinkAlert v-bind:fade="false" v-bind:pill="false" show="false" size="md" v-bind:isLink="true"
        v-bind:squared="false" hrefLink="" alertLabel="This alert will dismiss after time lapse" background="#17a2b8"
        buttonLabel="Show alert with count-down timer" v-bind:dismissible="false" alertVariant="primary"
        dismissLabel="Close" ncTypography="body1" verticalWidth="60px" buttonsVariant="primary"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'buttonLabel','displayName':'ButtonLabel'},{'type':'string','propName':'alertLabel','displayName':'AlertLabel'}]}"
        verticalHeight="60px" horizontalWidth="" progressVariant="primary" v-bind:dismissCountDown="5"
        horizontalHeight="" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
        ncClickBorderColor="#3d7bff" ncFocusBorderColor="#3d7bff" ncHoverBorderColor="#3d7bff"
        ncClickBackgroundColor="#3d7bff" ncFocusBackgroundColor="#3d7bff" ncHoverBackgroundColor="#3d7bff"
        position="absolute" top="41.78639240506329%" left="20.35326086956522%" id="a8f44d2f-250a-4b93-b54b-acee1c88edd3"
        v-bind:style="{'color':'#FFFFFF','width':'','height':'','fontSize':'9.008px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'225.2','lineHeight':'13.511999999999999px','marginLeft':'0px','paddingTop':'3.3779999999999997px','textShadow':'','visibility':'visible','borderColor':'#cce5ff','borderStyle':'none','marginRight':'0px','paddingLeft':'6.755999999999999px','marginBottom':'0px','paddingRight':'6.755999999999999px','paddingBottom':'3.3779999999999997px','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':9}"/>
      <WLightLinkAlert v-bind:fade="false" v-bind:pill="false" show="false" size="md" v-bind:isLink="true"
        v-bind:squared="false" hrefLink="" alertLabel="This alert will dismiss after time lapse" background="#17a2b8"
        buttonLabel="Show alert with count-down timer" v-bind:dismissible="false" alertVariant="light"
        dismissLabel="Close" ncTypography="body1" verticalWidth="60px" buttonsVariant="light"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'buttonLabel','displayName':'ButtonLabel'},{'type':'string','propName':'alertLabel','displayName':'AlertLabel'}]}"
        verticalHeight="60px" horizontalWidth="" progressVariant="light" v-bind:dismissCountDown="5" horizontalHeight=""
        ncClickFontColor="#000000" ncFocusFontColor="#000000" ncHoverFontColor="#000000" ncClickBorderColor="#f8f9fa"
        ncFocusBorderColor="#f8f9fa" ncHoverBorderColor="#f8f9fa" ncClickBackgroundColor="#f8f9fa"
        ncFocusBackgroundColor="#f8f9fa" ncHoverBackgroundColor="#f8f9fa" position="absolute" top="66.00474683544304%"
        left="25.088043478260868%" id="73e2a8ba-a873-40a3-a9e6-69697646debe"
        v-bind:style="{'color':'#000000','width':'','height':'','fontSize':'9.008px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'225.2','lineHeight':'13.511999999999999px','marginLeft':'0px','paddingTop':'3.3779999999999997px','textShadow':'','visibility':'visible','borderColor':'#f8f9fa','borderStyle':'none','marginRight':'0px','paddingLeft':'6.755999999999999px','marginBottom':'0px','paddingRight':'6.755999999999999px','paddingBottom':'3.3779999999999997px','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':10}"/>
      <WPrimaryAlert v-bind:fade="false" v-bind:pill="false" show="false" size="md" v-bind:isLink="false"
        v-bind:squared="false" hrefLink="" alertLabel="This alert will dismiss after time lapse" background="#17a2b8"
        buttonLabel="Show alert with count-down timer" v-bind:dismissible="false" alertVariant="primary"
        dismissLabel="Close" ncTypography="body1" verticalWidth="60px" buttonsVariant="primary"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'buttonLabel','displayName':'ButtonLabel'},{'type':'string','propName':'alertLabel','displayName':'AlertLabel'}]}"
        verticalHeight="60px" horizontalWidth="" progressVariant="primary" v-bind:dismissCountDown="5"
        horizontalHeight="" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
        ncClickBorderColor="#3d7bff" ncFocusBorderColor="#3d7bff" ncHoverBorderColor="#3d7bff"
        ncClickBackgroundColor="#3d7bff" ncFocusBackgroundColor="#3d7bff" ncHoverBackgroundColor="#3d7bff"
        position="absolute" top="47.96518987341772%" left="55.09347826086957%" id="f36753c1-18ff-41d6-882a-3920f5d8a22c"
        v-bind:style="{'color':'#FFFFFF','width':'','height':'','fontSize':'9.008px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'225.2','lineHeight':'13.511999999999999px','marginLeft':'0px','paddingTop':'3.3779999999999997px','textShadow':'','visibility':'visible','borderColor':'#cce5ff','borderStyle':'none','marginRight':'0px','paddingLeft':'6.755999999999999px','marginBottom':'0px','paddingRight':'6.755999999999999px','paddingBottom':'3.3779999999999997px','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':11}"/>
      <WDangerLinkAlert v-bind:fade="false" v-bind:pill="false" show="false" size="md" v-bind:isLink="true"
        v-bind:squared="false" hrefLink="" alertLabel="This alert will dismiss after time lapse" background="#17a2b8"
        buttonLabel="Show alert with count-down timer" v-bind:dismissible="false" alertVariant="danger"
        dismissLabel="Close" ncTypography="body1" verticalWidth="60px" buttonsVariant="danger"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'buttonLabel','displayName':'ButtonLabel'},{'type':'string','propName':'alertLabel','displayName':'AlertLabel'}]}"
        verticalHeight="60px" horizontalWidth="" progressVariant="danger" v-bind:dismissCountDown="5"
        horizontalHeight="" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
        ncClickBorderColor="#dc3545" ncFocusBorderColor="#dc3545" ncHoverBorderColor="#dc3545"
        ncClickBackgroundColor="#dc3545" ncFocusBackgroundColor="#dc3545" ncHoverBackgroundColor="#dc3545"
        position="absolute" top="40.984177215189874%" left="51.93152173913043%"
        id="00c4687e-eaf7-4a1c-9fb4-f6833bed11e2"
        v-bind:style="{'color':'#FFFFFF','width':'','height':'','fontSize':'9.008px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'225.2','lineHeight':'13.511999999999999px','marginLeft':'0px','paddingTop':'3.3779999999999997px','textShadow':'','visibility':'visible','borderColor':'#f8d7da','borderStyle':'none','marginRight':'0px','paddingLeft':'6.755999999999999px','marginBottom':'0px','paddingRight':'6.755999999999999px','paddingBottom':'3.3779999999999997px','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':12}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>