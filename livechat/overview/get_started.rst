==========================
Get Started with Live Chat
==========================

Real-time chat is a cost-effective tool and a great way to bring visitors back to your website. It
is an accessible and convenient customer support channel, and can increase efficiency, considering
that this way, support representatives can handle more than one case at a time.

Activate and set it up
======================

Once *Live Chat* is installed on your database, if your website was created with Odoo, the
application is automatically added to it. All that is left to do is to go to
:menuselection:`Website --> Configuration --> Settings --> Live Chat`.

.. image:: media/livechat_settings.png
   :align: center
   :height: 300
   :alt: View of the settings page and the live chat feature for Odoo Live Chat

Select the channel to be linked to your website or create one on the fly.

.. image:: media/channels.png
   :align: center
   :alt: View of a live chat channel form for Odoo Live Chat

| For both scenarios, under:
| - **Operators**: add agents to respond to the chat requests. Add as many as you like, and keep in
  mind that operators that do not show any activity in Odoo for more than 30min are considered
  disconnected.
| - **Options**: set the default text to be shown on the live chat button; an automated welcome
  message to be seen by visitors when a conversation is initiated, and the text that prompts the
  user to initiate a chat.
| - **Channel Rules**: choose an action for a given URL, and/or per country. In the example below,
  the chat window pops-up automatically after 3 seconds of users, from any country, landing on the
  contact us page.

.. image:: media/rules.png
   :align: center
   :alt: View of a channel’s rules form for Odoo Live Chat

.. note::
   GeoIP, which refers to the process of finding a computer terminal’s geographical location by its
   IP address, must be installed on your server. Otherwise, under *Channel Rules*, countries are
   not taken into account.

External options
----------------

| If your website was not created with Odoo, still in the channel form, under the *Widget* tab,
  copy and paste the code available to your website.
| Odoo also offers an URL you can send to users so they can have access to a single live chat page.

.. image:: media/widget.png
   :align: center
   :alt: View of the widget tab for Odoo Live Chat

Managing chat requests
======================

Conversations initiated by visitors pop up as a direct message, and are shown in *Discuss*.
Therefore, inquiries can be answered wherever you are in Odoo.

.. image:: media/discuss.png
   :align: center
   :alt: View of the discuss application with a message sent through live chat in Odoo

.. note::
   Conversations are dispatched based on the current workload of the online operators.

Leave or join a channel
=======================

Go to :menuselection:`Website --> Configuration --> Settings`, access your channel under
*Live Chat*, and *Join Channel* or *Leave Channel*.

.. image:: media/joinchannel.png
   :align: center
   :alt: View of a channel form and the option to join a channel for Odoo Live Chat

.. seealso::
   - :doc:`ratings`
   - :doc:`responses`