:mod:`cassandra` - Exceptions and Enums
=======================================

.. module:: cassandra

.. data:: __version_info__

   The version of the driver in a tuple format

.. data:: __version__

   The version of the driver in a string format

.. autoclass:: ConsistencyLevel
   :members:

.. autoclass:: UserFunctionDescriptor
   :members:
   :inherited-members:

.. autoclass:: UserAggregateDescriptor
   :members:
   :inherited-members:

.. autoexception:: Unavailable()
   :members:

.. autoexception:: Timeout()
   :members:

.. autoexception:: ReadTimeout()
   :members:

.. autoexception:: WriteTimeout()
   :members:

.. autoexception:: ReadFailure()
   :members:

.. autoexception:: WriteFailure()
   :members:

.. autoexception:: FunctionFailure()
   :members:

.. autoexception:: AlreadyExists()
   :members:

.. autoexception:: InvalidRequest()
   :members:

.. autoexception:: Unauthorized()
   :members:

.. autoexception:: AuthenticationFailed()
   :members:

.. autoexception:: OperationTimedOut()
   :members:
