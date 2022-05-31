<template>
 <sidebar-menu :menu="menu" />
</template>

<script>
import Dashboard from '@/assets/dashboard.png'
import Account from '@/assets/account.png'
import Contact from '@/assets/contact.png'
import Logout from '@/assets/logout.png'
import Medical from '@/assets/medical.png'
import Messages from '@/assets/messages.png'
import Profile from '@/assets/profile.png'
import Resources from '@/assets/resources.png'
import Services from '@/assets/services.png'
import Wallet from '@/assets/wallet.png'

export default {
  name: 'Sidebar',
  data() {
      return {
        menu: [
          {
            header: 'Main Navigation',
            hiddenOnCollapse: true
          },
          {
            href: '/',
            title: 'Dashboard',
            icon: {
              element: 'img',
              attributes: {src: Dashboard}
            }
          },
          {
            href: '/profile',
            title: 'Profile',
            icon: {
              element: 'img',
              attributes: {src: Profile}
            }
          },
          {
            href: '/services',
            title: 'Services',
            icon: {
              element: 'img',
              attributes: {src: Services}
            }
          },
          {
            href: '/medical-records',
            title: 'Medical Records',
            icon: {
              element: 'img',
              attributes: {src: Medical}
            }
          },
          {
            href: '/care-wallet',
            title: 'Care Wallet',
            icon: {
              element: 'img',
              attributes: {src: Wallet}
            }
          },
          {
            href: '/messages',
            title: 'Messages',
            icon: {
              element: 'img',
              attributes: {src: Messages}
            }
          },
          {
            href: '/resources',
            title: 'Resources',
            icon: {
              element: 'img',
              attributes: {src: Resources}
            }
          },
          {
            href: '/account-settings',
            title: 'Account Settings',
            icon: {
              element: 'img',
              attributes: {src: Account}
            }
          },
          {
            href: '/contact-support',
            title: 'Contact Support',
            icon: {
              element: 'img',
              attributes: {src: Contact}
            }
          },
          {
            href: '/logout',
            title: 'Logout',
            icon: {
              element: 'img',
              attributes: {src: Logout}
            }
          }
        ]
      }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.v-sidebar-menu{
  background: #ffffff;
  border-right: 1px solid #0000001e;
}
.vsm--link .vsm--link_level-1{
  color: #000000;
}
.vsm--icon{
  background-color: none !important;
} 
</style>
