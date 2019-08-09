##########################
Module ``proton.handlers``
##########################

.. currentmodule:: proton.handlers

Module Summary
##############

|

.. autosummary::

    MessagingHandler
    EndpointStateHandler
    IncomingMessageHandler
    OutgoingMessageHandler
    TransactionHandler
    TransactionalClientHandler

|

Exceptions
==========

|

.. autosummary::

    Reject
    Release

|

Module Detail
#############

|

.. autoclass:: proton.handlers.MessagingHandler
    :members:
    :show-inheritance:
    :inherited-members:
    :undoc-members:
    :exclude-members: handlers, add

------------

.. autoclass:: proton.handlers.EndpointStateHandler
    :members:
    :show-inheritance:
    :inherited-members:
    :undoc-members:
    :exclude-members: handlers, add, on_link_remote_close, on_session_remote_close, on_connection_remote_close, on_connection_local_open, on_connection_remote_open, on_session_local_open, on_session_remote_open, on_link_local_open, on_link_remote_open

------------

.. autoclass:: proton.handlers.IncomingMessageHandler
    :members:
    :show-inheritance:
    :inherited-members:
    :undoc-members:
    :exclude-members: handlers, add, on_delivery

------------

.. autoclass:: proton.handlers.OutgoingMessageHandler
    :members:
    :show-inheritance:
    :inherited-members:
    :undoc-members:
    :exclude-members: handlers, add, on_link_flow, on_delivery

------------

.. autoclass:: proton.handlers.TransactionHandler
    :members:
    :show-inheritance:
    :inherited-members:
    :undoc-members:

------------

.. autoclass:: proton.handlers.TransactionalClientHandler
    :members:
    :show-inheritance:
    :inherited-members:
    :undoc-members:
    :exclude-members: handlers, add

------------

.. autoclass:: proton.handlers.Reject
    :members:
    :show-inheritance:
    :inherited-members:
    :undoc-members:

------------

.. autoclass:: proton.handlers.Release
    :members:
    :show-inheritance:
    :inherited-members:
    :undoc-members:

