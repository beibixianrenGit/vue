@touchmove.stop.prevent="moveHandle"
svn账号
git账号：qiukaijiang     qkj123456
	http://git.weidunshuju.com:8082/summary/docs.git
gitlab账号： qiukaijiang@yinzetong.com         qkj123456
	http://git.weidunshuju.com:10081/web/znkb-console
git聚风科技账号:   qiukaijiang     kaijiang520
	https://git.gatwinpay.cn
聚风后台账号：superadmin		a123456
	jufeng		a123456
	jufeng1		a123456
	jufeng2		a123456
聚风app账号：15770584383		qqq111
线上打包：https://jenkins.gatwinpay.cn
账密：admin		admin
聚风禅道：http://218.17.189.13:8340/zentao/company-browse.html
账号：liuqiang  密码：liuqiang123

// 弹窗组件
import showModal from "@/components/showModal/showModal.vue";
components: {
			showModal
		},
<showModal :show="tuijianShow" title="我的推荐人" :content="tjContent" confirmText="拨打电话" align="center" @onCancel="onCancel" @onConfirm="onConfirm"></showModal>

<!-- icon -->
import uniIcons from "@/components/uni-icons/uni-icons.vue"
components: {uniIcons},
<uni-icons color="#ccc" type="forward" size="24"></uni-icons>
