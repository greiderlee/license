1.��mac.license�ļ����ڲ��������������λ�ö����Բ���¼���·��
2.�ý�ѹ�����isoftstone_license.jar�ҵ�license.properties�����ļ�
�޸�licensePath=E:\\mac.license(��Ϊ1��mac.license���·��)   
expirePage=/license_expired.jsp(Ϊlicense���ں�redirect·��,���Է�һ����ʾlicense���ڵ�ҳ��)
��root-license.xml�����ļ�,<aop:pointcut id="licenseCheck" expression="execution(* org.bdp.modules.*.*.controller..*.*(..))"/>
�޸���Ҫ��֤license��controller
3.���޸ĺ��isoftstone_license.jar�������WEB-INFO/lib��
4.��public.store�ļ�������Ŀ��classes��
5.��spring-mvc�����ļ��м���<import resource="root-license.xml"/>������Ŀ���ɽ���license����֤